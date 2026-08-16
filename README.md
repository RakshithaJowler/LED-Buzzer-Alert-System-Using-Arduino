# LED-Buzzer-Alert-System-Using-Arduino

## Description

A simple embedded system project using Arduino to control an LED and buzzer as an alert system.

## Components

- Arduino Uno
- LED
- 220Ω Resistor
- Piezo Buzzer
- Breadboard
- Jumper Wires

## Working

The Arduino controls the LED through digital pin 13 and the buzzer through digital pin 8. The LED and buzzer turn ON for 1 second and OFF for 1 second continuously.

## Programming

Arduino C/C++

int led = 13;
int buzzer = 8;

void setup() {
  pinMode(led, OUTPUT);
  pinMode(buzzer, OUTPUT);
}

void loop() {
  digitalWrite(led, HIGH);
  digitalWrite(buzzer, HIGH);
  delay(1000);

  digitalWrite(led, LOW);
  digitalWrite(buzzer, LOW);
  delay(1000);
}

## Project Image 
![LED and Buzzer Alert System](./image.png)
