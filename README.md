# CNC Robot Machine Printer

This project is a **CNC robot machine printer** built using embedded systems and/or computer control logic. The system interprets G-code instructions to move a pen or a toolhead across X, Y, and Z axes to create precise drawings or engravings.

## 🔧 Features

- Interprets basic G-code commands (G00, G01, etc.)
- Supports X, Y (and optional Z) axis movement
- Stepper motor control for precise positioning
- Endstop support for axis calibration
- Serial communication for command input
- Pen up/down mechanism for printing/drawing

## 📦 Components Used

- Arduino UNO
- Stepper motors with drivers (e.g., A4988)
- Servo motor (for pen up/down)
- Power supply
- CNC Frame (custom or recycled parts)
- USB interface to PC (for G-code sending)

## 🧠 How It Works

1. The machine receives G-code instructions via Serial.
2. Arduino parses the G-code and calculates the step count.
3. Stepper motors move accordingly to reach the target position.
4. Pen mechanism is controlled with a servo to lift or draw.



