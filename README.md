# LED 8x8 Dot Matrix using Arduino

This project demonstrates how to control an 8x8 LED dot matrix display using an Arduino and the `LedControl` library. The code initializes the matrix, displays a predefined pattern, and refreshes it every second.

---

## Features
- Control an 8x8 LED dot matrix with minimal wiring.
- Display custom patterns using an array of bytes.
- Adjustable brightness and power-saving mode.

---

## Hardware Requirements
- **Arduino Board** (e.g., Uno, Nano, Mega)
- **MAX7219/MAX7221 LED Dot Matrix Module** (8x8)
- Jumper Wires
- Breadboard (optional)

---

## Circuit Diagram
| **Arduino Pin** | **Matrix Pin** |
|------------------|----------------|
| 12 (DIN)         | DIN            |
| 11 (CS)          | CS             |
| 10 (CLK)         | CLK            |
| GND              | GND            |
| 5V               | VCC            |

---

## Software Requirements
- Arduino IDE
- [`LedControl` Library](https://github.com/wayoda/LedControl)

---

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/led-dot-matrix-arduino.git
   cd led-dot-matrix-arduino
