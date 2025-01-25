# DLD 2-Bit Calculator

This repository contains the implementation of a **Digital Logic Design 2-Bit Calculator**. The calculator supports four operations: addition, subtraction, multiplication, and squaring, with additional MUX functionality and a 7-segment display integration.

## Project Details

**Done by:** Anas Wagih


---

## Features

### 1. Addition
- **Logic Used:** Full Adder IC (4-bit parallel binary adder)
- **Inputs:** A (A1, A2, A3, A4), B (B1, B2, B3, B4)
- **Description:** Adds two 2-bit numbers.
- **Circuit:** Refer to `addition_circuit.png`

---

### 2. Subtraction
- **Logic Used:** 7483 Full Adder IC with 7404 NOT Gate
- **Inputs:** A, B (two's complement logic applied to B)
- **Description:** Subtracts B from A when A ≥ B.
- **Circuit:** Refer to `subtraction_circuit.png`

---

### 3. Multiplication
- **Logic Used:** Basic AND, OR, and XOR Gates
- **Description:** Multiplies two 2-bit numbers using simplified logic derived from truth tables.
- **Circuit:** Refer to `multiplication_circuit.png`

---

### 4. Power (Squaring)
- **Logic Used:** AND and NOT Gates
- **Description:** Squares a 2-bit number A based on truth table simplifications using Karnaugh maps.
- **Circuit:** Refer to `power_circuit.png`

---

### 5. MUX
- **Description:** Used to combine and control signals from various operations.
- **Circuit:** Refer to `mux_circuit.png`

---

### 6. 7-Segment Display
- **Logic Used:** 7447 Decoder IC
- **Description:** Displays the output of operations in decimal format.
- **Circuit:** Refer to `7segment_circuit.png`


## How It Works
1. The calculator uses **ICs** like 7483 Full Adder and 7447 Decoder for implementing addition and display functions.
2. Logical gates (AND, OR, NOT, XOR) are used for multiplication, subtraction, and power operations.
3. Multiplexers (MUX) control signals and route outputs appropriately.
4. Results are displayed using a 7-segment decoder.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

