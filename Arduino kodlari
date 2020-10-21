#define led 3


void setup() {
  pinMode(led,OUTPUT);
  Serial.begin(9600);
  
}

void loop() {
  int isik= analogRead(A0);
 Serial.println(isik);
 delay(100);

// if(isik>800){
//  digitalWrite(led,LOW);
//  }
// if(isik<700){
// digitalWrite(led,HIGH);
// }
// aynı gorevı goruyor

 if(isik>800)
  digitalWrite(led,LOW);
 else
 digitalWrite(led,HIGH);

 
}
