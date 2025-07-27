# HuskyLens Face Recognition with Arduino

This project shows how to use the HuskyLens AI Camera with an Arduino Uno via UART (SoftwareSerial). The Arduino reads data from HuskyLens and prints details about detected objects or faces.

---

## Features

- Communicates with HuskyLens using UART serial at 9600 baud.
- Checks if HuskyLens is connected and if anything is learned.
- Prints detected blocks (faces/objects) and arrows with their position and ID.

---

## Hardware Required

| Component          | Quantity | Notes                         |
|--------------------|----------|-------------------------------|
| HuskyLens AI Camera | 1        | Set to UART 9600 protocol      |
| Arduino Uno        | 1        | Or compatible board            |
| Jumper Wires       | 4        | For connections                |

---

## Wiring (UART via SoftwareSerial)

| HuskyLens Pin | Arduino Pin     |
|---------------|-----------------|
| TX (green)    | Pin 10 (Arduino RX) |
| RX (blue)     | Pin 11 (Arduino TX) |
| VCC           | 5V              |
| GND           | GND             |


