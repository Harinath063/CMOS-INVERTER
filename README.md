# 🔌 CMOS Inverter Simulation using Proteus

## 📌 Overview

This project demonstrates the design and simulation of a **CMOS Inverter** using **Proteus Design Suite**.
A CMOS inverter is the most basic digital logic gate, built using a combination of **PMOS** and **NMOS** transistors.

The inverter performs the logical operation:

* Input `0` → Output `1`
* Input `1` → Output `0`

---

## 🎯 Objective

* To design a CMOS inverter circuit
* To simulate its behavior using Proteus
* To verify the inversion property using binary input signals
* To observe output using an LED indicator

---

## 🧰 Tools Used

* Proteus Design Suite (for simulation)
* CMOS Transistors (PMOS & NMOS)
* Voltage Sources (VDD and Input)
* LED (as output indicator)
* Resistor (for current limiting)

---

## ⚙️ Circuit Description

The CMOS inverter consists of:

* **PMOS transistor** connected to VDD
* **NMOS transistor** connected to Ground
* Both gates connected together as input
* Drains connected together as output

### 🔌 Connections:

* PMOS Source → VDD (5V)
* NMOS Source → GND
* Gates → Input Voltage Source
* Drains → Output Node
* Output → Resistor → LED → GND

---

## 🔄 Working Principle

### Case 1: Input = 0 (LOW)

* PMOS → ON
* NMOS → OFF
* Output → HIGH (5V)
* LED → ON ✅

### Case 2: Input = 1 (HIGH)

* PMOS → OFF
* NMOS → ON
* Output → LOW (0V)
* LED → OFF ❌

---

## 📊 Simulation Details

* VDD = 5V (DC Source)
* Input Signal = Binary (0V / 5V)
* LED used to visualize output
* Resistor value = 1kΩ

---

## 📸 Output Observation

| Input | Output Voltage | LED Status |
| ----- | -------------- | ---------- |
| 0V    | ~5V            | ON         |
| 5V    | ~0V            | OFF        |

---

## 🚀 Key Learnings

* Understanding CMOS inverter operation
* Difference between analog voltage and digital logic
* Importance of proper transistor connections
* Role of resistor in protecting LED
* Basic digital circuit simulation

---

## 📁 Files Included

* Proteus schematic file (.dsn)
* Simulation screenshots (optional)

---

## 📌 Applications

* Digital logic design
* VLSI circuits
* Microprocessor and FPGA design
* Basic building block for NAND, NOR gates

---

## 🙌 Conclusion

The CMOS inverter successfully demonstrates the fundamental concept of logic inversion.
This project builds a strong foundation for more advanced digital and VLSI circuit design.

---

## ⭐ Author

V.Venkata Harinath
Diploma 2nd year ECE TIRUPATI SVGP.

If you found this project helpful, consider giving it a ⭐ on GitHub!
