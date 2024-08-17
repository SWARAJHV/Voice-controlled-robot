# Voice-controlled-robot
Voice-Controlled Robot with Arduino and Bluetooth
Overview
This project involves building a voice-controlled robot using an Arduino microcontroller, a Bluetooth module, and an L298 motor driver IC. The robot can detect and respond to voice commands via a smartphone or any Bluetooth-enabled device.

Components Required
Arduino Uno or compatible board
Bluetooth module (HC-05/HC-06)
L298N Motor Driver IC
DC Motors (x2)
Robot chassis with wheels
9V or 12V Battery pack
Jumper wires
Breadboard (optional)
Voice command application (e.g., Android app like "Arduino Voice Control")
Circuit Diagram
Connections:
Bluetooth Module (HC-05/HC-06)

VCC to 5V on Arduino
GND to GND on Arduino
TXD to RX (Pin 0) on Arduino
RXD to TX (Pin 1) on Arduino
L298N Motor Driver IC

IN1 to Arduino Pin 2
IN2 to Arduino Pin 3
IN3 to Arduino Pin 4
IN4 to Arduino Pin 5
ENA to Arduino Pin 9 (PWM control)
ENB to Arduino Pin 10 (PWM control)
Motor A to Motor 1 terminals
Motor B to Motor 2 terminals
VCC to Battery Positive (+)
GND to Battery Negative (-) and Arduino GND
12V Motor Supply to the motor's external power supply (+)
Power Supply

Connect the battery pack to power the motor driver and Arduino.
Software Setup
Arduino IDE:
Install the Arduino IDE from the official website.
Connect the Arduino board to your computer using a USB cable.
Select the appropriate board and port under Tools > Board and Port.
