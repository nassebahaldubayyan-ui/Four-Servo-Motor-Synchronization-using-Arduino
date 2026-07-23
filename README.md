# Four Servo Motor Synchronization using Arduino

![Arduino](https://img.shields.io/badge/Arduino-Uno-00979D)
![Simulation](https://img.shields.io/badge/Simulation-Tinkercad-orange)
![Language](https://img.shields.io/badge/Language-C%2B%2B-blue)
![Servos](https://img.shields.io/badge/Servo_Motors-4-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## Introduction

This project demonstrates how to control four servo motors simultaneously using an Arduino Uno in a Tinkercad simulation. The program runs the standard Servo Sweep example for two seconds before automatically positioning all four servo motors at **90°**, where they remain stationary. The project introduces the fundamentals of servo motor control, synchronization, and Arduino programming.

---

## Project Preview

### Simulation

<p align="center">
  <img src="images/demo.gif" width="700">
</p>

### Circuit Design

<p align="center">
  <img src="images/circuit.png" width="700">
</p>

---

## Features

- Control four servo motors simultaneously
- Simulated using Tinkercad
- Servo Sweep motion for 2 seconds
- Automatically moves all servos to 90°
- Uses the Arduino Servo library
- Beginner-friendly Arduino project

---

## Components Used

- Arduino Uno
- 4 Servo Motors
- Jumper Wires
- Tinkercad Simulation
- Arduino IDE (C++)

---

## Wiring

| Servo Motor | Arduino Pin |
|-------------|-------------|
| Servo 1 | D6 |
| Servo 2 | D3 |
| Servo 3 | D9 |
| Servo 4 | D5 |
| Power | 5V |
| Ground | GND |

---

## How It Works

1. Initialize four servo motors.
2. Attach each servo to its assigned digital pin.
3. Run the Servo Sweep motion for 2 seconds.
4. Move all four servo motors together from 0° to 180° and back.
5. After two seconds, position every servo at 90°.
6. Keep all motors holding the 90° position.

---

## Implementation Steps

1. Created the circuit in Tinkercad.
2. Connected four servo motors to the Arduino Uno.
3. Powered all servos using the Arduino 5V and GND pins.
4. Attached the servos to digital pins **9, 6, 5, and 3**.
5. Imported the Arduino Servo library.
6. Programmed all four servos to move together using the Servo Sweep example.
7. Limited the sweep operation to **2 seconds** using `millis()`.
8. Positioned every servo at **90°** after the sweep.
9. Tested the simulation to verify all motors behaved correctly.

---

## Author

**Nassebah Al-Dubayyan**

Computer Science Student | AI & Software Development Enthusiast
