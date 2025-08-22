# Button-Controlled-LEDs-with-Arduino

# Overview
This project demonstrates how to control three LEDs using three push buttons and an
Arduino UNO in Tinkercad.
Each button is connected with a pull-down resistor (10 kΩ) and controls one LED.
- Button 1 → LED 1
- Button 2 → LED 2
- Button 3 → LED 3
When a button is pressed, the corresponding LED lights up. When released, the LED turns off.

# Components Used
- 1 × Arduino UNO
- 1 × Breadboard
- 3 × Push Buttons
- 3 × LEDs
- 3 × Resistors 220Ω (for LEDs)
- 3 × Resistors 10kΩ (pull-down for buttons)
- Jumper Wires
  # Circuit Connections
   Buttons:
- One leg connected to +5V.
- Second leg connected to Arduino pins 2, 3, 4.
- Same leg also connected to GND through a 10kΩ pull-down resistor.
  LEDs:
- Anode (long leg) connected to Arduino pins 8, 9, 10 via 220Ω resistors.
- Cathode (short leg) connected to GND.
