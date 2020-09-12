# traffic-light-system
Arduino based traffic light system.
#include <LiquidCrystal.h>
LiquidCrystal mylcd(12,13,A0,A1,A2,A3);
int red=2;
int yellow=3;
int green=4;
int COUNT=0;
int a =5;
int b=6;
int c=7;
int d=8;
int e=9;
int f=10;
int g=11;
void setup()
{
  pinMode(red,OUTPUT);
  pinMode(yellow,OUTPUT);
  pinMode(green,OUTPUT);
  pinMode(a,OUTPUT);
  pinMode(b,OUTPUT);
  pinMode(c,OUTPUT);
  pinMode(d,OUTPUT);
  pinMode(e,OUTPUT);
  pinMode(f,OUTPUT);
  pinMode(g,OUTPUT);
  mylcd.begin(16,2);
  mylcd.home();
  }
 void loop()
 {
  mylcd.print("TRAFFIC SIGNAL");
 delay(2000);
  mylcd.clear();
  mylcd.print("STOP");
  delay(500);
  digitalWrite(2,HIGH);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  
  digitalWrite(5,HIGH);
    digitalWrite(10,LOW);
      digitalWrite(11,HIGH);
        digitalWrite(7,HIGH);
          digitalWrite(8,HIGH);
             digitalWrite(6,HIGH);
          digitalWrite(9,LOW);
          delay(500);
           digitalWrite(5,HIGH);
    digitalWrite(10,LOW);
      digitalWrite(11,HIGH);
        digitalWrite(7,LOW);
          digitalWrite(8,HIGH);
             digitalWrite(6,HIGH);
          digitalWrite(9,HIGH);
          delay(500);
               digitalWrite(5,LOW);
    digitalWrite(10,LOW);
      digitalWrite(11,LOW);
        digitalWrite(7,HIGH);
          digitalWrite(8,LOW);
             digitalWrite(6,HIGH);
          digitalWrite(9,LOW);
          delay(500);
                     digitalWrite(5,HIGH);
    digitalWrite(10,HIGH);
      digitalWrite(11,LOW);
        digitalWrite(7,HIGH);
          digitalWrite(8,HIGH);
             digitalWrite(6,HIGH);
          digitalWrite(9,HIGH);
          delay(500);
          
          

  mylcd.clear();
  mylcd.print("READY");
  delay(500);
  digitalWrite(2,LOW);
  digitalWrite(3,HIGH);
  digitalWrite(4,LOW);
   digitalWrite(5,HIGH);
    digitalWrite(10,LOW);
      digitalWrite(11,HIGH);
        digitalWrite(7,HIGH);
          digitalWrite(8,HIGH);
             digitalWrite(6,HIGH);
          digitalWrite(9,LOW);
          delay(500);
           digitalWrite(5,HIGH);
    digitalWrite(10,LOW);
      digitalWrite(11,HIGH);
        digitalWrite(7,LOW);
          digitalWrite(8,HIGH);
             digitalWrite(6,HIGH);
          digitalWrite(9,HIGH);
          delay(500);
               digitalWrite(5,LOW);
    digitalWrite(10,LOW);
      digitalWrite(11,LOW);
        digitalWrite(7,HIGH);
          digitalWrite(8,LOW);
             digitalWrite(6,HIGH);
          digitalWrite(9,LOW);
          delay(500);
                     digitalWrite(5,HIGH);
    digitalWrite(10,HIGH);
      digitalWrite(11,LOW);
        digitalWrite(7,HIGH);
          digitalWrite(8,HIGH);
             digitalWrite(6,HIGH);
          digitalWrite(9,HIGH);
          delay(500);
  mylcd.clear();
  mylcd.print("GO");
  delay(500);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,HIGH);
   digitalWrite(5,HIGH);
    digitalWrite(10,LOW);
      digitalWrite(11,HIGH);
        digitalWrite(7,HIGH);
          digitalWrite(8,HIGH);
             digitalWrite(6,HIGH);
          digitalWrite(9,LOW);
          delay(500);
           digitalWrite(5,HIGH);
    digitalWrite(10,LOW);
      digitalWrite(11,HIGH);
        digitalWrite(7,LOW);
          digitalWrite(8,HIGH);
             digitalWrite(6,HIGH);
          digitalWrite(9,HIGH);
          delay(500);
               digitalWrite(5,LOW);
    digitalWrite(10,LOW);
      digitalWrite(11,LOW);
        digitalWrite(7,HIGH);
          digitalWrite(8,LOW);
             digitalWrite(6,HIGH);
          digitalWrite(9,LOW);
          delay(500);
                     digitalWrite(5,HIGH);
    digitalWrite(10,HIGH);
      digitalWrite(11,LOW);
        digitalWrite(7,HIGH);
          digitalWrite(8,HIGH);
             digitalWrite(6,HIGH);
          digitalWrite(9,HIGH);
          delay(500);

  mylcd.clear();
                   digitalWrite(5,LOW);
    digitalWrite(10,LOW);
      digitalWrite(11,LOW);
        digitalWrite(7,LOW);
          digitalWrite(8,LOW);
             digitalWrite(6,LOW);
          digitalWrite(9,LOW);
            digitalWrite(2,LOW);
             digitalWrite(3,LOW);
          digitalWrite(4,LOW);
        
        
         
 }
