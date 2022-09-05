# Embedded Traffic Light System

# Project Description: 
A traffic light system implemented using C programming language, TivaC board, breadboard, switches ,LEDs, and jumper wires for connections. The whole idea of the project is to implement a basic traffic lightning system for two intersecting streets. When the first street is on the green light, the other shoud be put on hold (the red LED on) until the first street changes to the red light. Each light has a specific number of seconds during which it should be kept on:
  1. RED Light: on until the other street's traffic light turn red.
  2. Yellow Light: 2 sec.
  3. Green Light: 5 sec.

After implementing the normal traffic light, the two switches were used to implement the presence of pedestrians crossing the streets. In this case, when any of the 2 switches are pressed, the corresponding traffic light will automatically turn red allowing the pedestrian to cross the street.

# Objectives:
 1. Timers: using timers to configure the span of the traffic lights.
 2. GPIO: using LEDs as outputs, and push buttons as input.
 3. Interrupts: use interrupts also in this project for the push buttons and timers.
