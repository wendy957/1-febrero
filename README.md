# 1-febrero
int ledR = 13;
int ledG = 12;
int ledB = 11;
int enc = 50;
int apa = 10;

void setup() {
pinMode(ledR,OUTPUT);
pinMode(ledG,OUTPUT);
pinMode(ledB,OUTPUT);
}

void loop() {
digitalWrite(ledR,HIGH);
delay(enc);
digitalWrite(ledR,LOW);
delay(apa);
digitalWrite(ledG,HIGH);
delay(enc);
digitalWrite(ledG,LOW);
delay(apa);
digitalWrite(ledB,HIGH);
delay(enc);
digitalWrite(ledB,LOW);
delay(apa);
}
