Lab 1.1:
```
void setup() {
  pinMode(13, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);
  delay(1000);
  digitalWrite(13, LOW);
  delay(1000);
}
```
<br>




Lab 1.2:
```
void setup() {
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
  pinMode(11, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);
  delay(250);
  digitalWrite(13, LOW); 
  delay(250);
  digitalWrite(12, HIGH);
  delay(250);
  digitalWrite(12, LOW);
  delay(250);
  digitalWrite(11, HIGH);
  delay(250);
  digitalWrite(11, LOW); 
  delay(250);
}
```
<br>




Lab 1.2.1:
```
void setup() {
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
  pinMode(11, OUTPUT);
  pinMode(10, OUTPUT);
}

void loop() {
  kelip(13);
  kelip(12);
  kelip(11);
  kelip(10);
}

void kelip(int pin) {
  digitalWrite(pin, HIGH);
  delay(250);
  digitalWrite(pin, LOW);
  delay(250);
}
```
<br>




Lab 1.3:
```
void setup() {
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
  pinMode(11, OUTPUT);
}

void loop() {
  kelip(13, 2000);
  kelip(12, 500);
  kelip(11, 1500);
}

void kelip(int pin, int masa) {
  digitalWrite(pin, HIGH); 
  delay(masa); 
  digitalWrite(pin, LOW);
}
```
<br>




Lab 1.4:
```
void setup() {
  tone(7, 262, 250);
  delay(250 * 1.30);
  tone(7, 196, 125);
  delay(125 * 1.30);
  tone(7, 196, 125);
  delay(125 * 1.30);
  tone(7, 220, 250);
  delay(250 * 1.30);
  tone(7, 196, 250);
  delay(250 * 1.30);
  tone(7, 247, 250);
  delay(250 * 1.30);
  tone(7, 247, 250);
  delay(250 * 1.30);
  tone(7, 262, 250);
  delay(250 * 1.30);
}

void loop() {
}
```
<br>




Lab 2.1:
```
int red = 9;

void setup() {
  pinMode(red, OUTPUT);
}

void loop() {
  analogWrite(red, 0);
  delay(1000);
  analogWrite(red, 10);
  delay(1000);
  analogWrite(red, 20);
  delay(1000);
  analogWrite(red, 30);
  delay(1000);
  analogWrite(red, 40);
  delay(1000);
}
```
<br>




Lab 2.2:
```
void setup() {
  pinMode(9, OUTPUT);
  pinMode(10, OUTPUT);
  pinMode(11, OUTPUT);
}

void loop() {
  analogWrite(9, random(0, 225));
  analogWrite(10, random(0, 225));
  analogWrite(11, random(0, 225));
  tone(7, 262, 250);
  delay(250 * 1.30);
  
  analogWrite(9, random(0, 225));
  analogWrite(10, random(0, 225));
  analogWrite(11, random(0, 225));
  tone(7, 196, 125);
  delay(125 * 1.30);
  
  analogWrite(9, random(0, 225));
  analogWrite(10, random(0, 225));
  analogWrite(11, random(0, 225));
  tone(7, 196, 125);
  delay(125 * 1.30);
  
  analogWrite(9, random(0, 225));
  analogWrite(10, random(0, 225));
  analogWrite(11, random(0, 225));
  tone(7, 220, 250);
  delay(250 * 1.30);
  
  analogWrite(9, random(0, 225));
  analogWrite(10, random(0, 225));
  analogWrite(11, random(0, 225));
  tone(7, 196, 250);
  delay(250 * 1.30);
  
  analogWrite(9, random(0, 225));
  analogWrite(10, random(0, 225));
  analogWrite(11, random(0, 225));
  tone(7, 247, 250);
  delay(250 * 1.30);
  
  analogWrite(9, random(0, 225));
  analogWrite(10, random(0, 225));
  analogWrite(11, random(0, 225));
  tone(7, 247, 250);
  delay(250 * 1.30);
  
  analogWrite(9, random(0, 225));
  analogWrite(10, random(0, 225));
  analogWrite(11, random(0, 225));
  tone(7, 262, 250);
  delay(250 * 1.30);
}
```
<br>




Lab 3.0:
```
void setup() {
  pinMode(9, INPUT);
  pinMode(5, OUTPUT);
}

void loop() {
  if (digitalRead(9) == HIGH) {
    digitalWrite(5, HIGH);
  } else {
    digitalWrite(5, LOW);
  }
}
```
<br>




Lab 4.1:
```
void setup() {
  Serial.begin(9600);
}

void loop() {
  int Dout = analogRead(A0);
  float Vin = Dout * 0.00488;
  Serial.print("voltage: ");
  Serial.println(Vin);
  delay(100);
}
```
<br>




Lab 4.2:
```
void setup() {
  pinMode(9, OUTPUT);
}

void loop() {
  int pot = analogRead(A0);
  pot = map(pot, 0, 1023, 0, 255);
  analogWrite(9, pot);
}
```
<br>




Lab 4.3:
```
int LDR_Pin = A0; //analog pin A0

void setup() {
  Serial.begin(9600);
  pinMode(2, OUTPUT);
}

void loop() {
  int LDRReading = analogRead(LDR_Pin);
  float Vout = LDRReading * 0.00488; //Convert readings to voltage
  Serial.println(Vout);
  delay(250); //just here to slow down the output for easier reading
  if (Vout > 1.0) {
    digitalWrite(2, HIGH);
  } else {
    digitalWrite(2, LOW);
  }
}
```
<br>




Lab 4.4:
```
void setup() {
  Serial.begin(9600);
}

void loop() {
  int Dout = analogRead(A0);
  float Vin = Dout * 0.00488;
  float temp = Vin * 100;
  Serial.println(temp);
  delay(100);
}
```
<br>




Lab 5.1:
```
#include <LiquidCrystal.h>
LiquidCrystal lcd(8, 9, 10, 11, 12, 13); //RS, EN, D4, D5, D6, D7

void setup() {
  lcd.begin(16, 2);
  lcd.print("hello, world!");
}

void loop() {
  lcd.setCursor(0, 1);
  lcd.print(millis() / 1000);
}
```
<br>




Lab 5.2:
```
#include <SimpleDHT.h>
int pinDHT11 = 2;
SimpleDHT11 dht11(pinDHT11);

void setup() {
  Serial.begin(9600);
}

void loop() {
  //start working..
  Serial.println("Sample DHT11...");
  //read without samples.
  byte temperature = 0;
  byte humidity = 0;
  //read temperature and humidity value to PC.
  Serial.print("Sample OK: ");
  Serial.print((int)temperature); 
  Serial.print(" C, ");
  Serial.print((int)humidity); 
  Serial.println(" H");
  //DHT11 sampling rate is 1HZ.
  //it is a must to have this delay when working DHT11.
  delay(1500);
}
```
<br>




Lab 5.3:
```
#include <Wire.h>
#include "RTClib.h"
RTC_DS1307 RTC;

void setup() {
  Serial.begin(9600);
  Wire.begin();
  RTC.begin();
  if (!RTC.isrunning()) {
    Serial.println("RTC is NOT running!");
    // This will reflect the time that your sketch was compiled
    RTC.adjust(DateTime(__DATE__, __TIME__));
  }
}

void loop() {
  DateTime now = RTC.now();
  Serial.print(now.month(), DEC);
  Serial.print('/');
  Serial.print(now.day(), DEC);
  Serial.print('/');
  Serial.print(now.year(), DEC);
  Serial.print(' ');
  Serial.print(now.hour(), DEC);
  Serial.print(':');
  Serial.print(now.minute(), DEC);
  Serial.print(':');
  Serial.print(now.second(), DEC);
  Serial.println();
  delay(1000);
}
```
<br>




Lab 6.1:
```
```
<br>




Lab 6.2:
```
```
<br>



