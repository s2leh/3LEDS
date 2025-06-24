# 3LEDS
This project demonstrates how to control three LEDs connected to an Arduino board. Each LED turns on and off sequentially with a delay between each action. It's a simple yet effective example for beginners to understand the basics of digital output and timing in Arduino.

Components Used
1 × Arduino board (Uno, Nano, etc.)

3 × LEDs

3 × Resistors (220 ohm)

Breadboard

Jumper wires

Circuit Diagram
LED 1 → Digital Pin 13 (with 220Ω resistor to GND)

LED 2 → Digital Pin 12 (with 220Ω resistor to GND)

LED 3 → Digital Pin 11 (with 220Ω resistor to GND)

How It Works
Each LED is turned on for 1 second, then turned off for 0.5 seconds. The sequence runs from Pin 13 to Pin 11, repeating in a loop:

Turn on LED on pin 13 → wait 1s → turn off → wait 0.5s

Turn on LED on pin 12 → wait 1s → turn off → wait 0.5s

Turn on LED on pin 11 → wait 1s → turn off → wait 0.5s

Repeat the sequence
