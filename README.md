# Design and Simulation of Half Adder and Full Adder Using Logisim

## 📌 Project Overview

This project focuses on the design and simulation of Half Adder and Full Adder circuits using Logisim. The circuits are designed using basic logic gates and their outputs are verified using truth tables.

## 🎯 Objectives

- To understand the concept of binary addition.
- To design and simulate a Half Adder using Logisim.
- To design and simulate a Full Adder using Logisim.
- To verify the outputs using truth tables.
- To understand the difference between Half Adder and Full Adder.

## 🛠️ Software Used

- Logisim
- GitHub

## 🔹 Half Adder

A Half Adder is a combinational logic circuit that adds two single-bit binary numbers.

**Inputs:** A, B

**Outputs:** Sum, Carry

The Sum is obtained using an XOR gate and the Carry is obtained using an AND gate.

## 🔹 Full Adder

A Full Adder is a combinational logic circuit that adds three single-bit binary inputs.

**Inputs:** A, B, Cin

**Outputs:** Sum, Cout

The Full Adder can be implemented using two Half Adders and an OR gate.

## 📊 Truth Tables

### Half Adder

| A | B | Sum | Carry |
|---|---|-----|-------|
| 0 | 0 | 0 | 0 |
| 0 | 1 | 1 | 0 |
| 1 | 0 | 1 | 0 |
| 1 | 1 | 0 | 1 |

### Full Adder

| A | B | Cin | Sum | Cout |
|---|---|-----|-----|------|
| 0 | 0 | 0 | 0 | 0 |
| 0 | 0 | 1 | 1 | 0 |
| 0 | 1 | 0 | 1 | 0 |
| 0 | 1 | 1 | 0 | 1 |
| 1 | 0 | 0 | 1 | 0 |
| 1 | 0 | 1 | 0 | 1 |
| 1 | 1 | 0 | 0 | 1 |
| 1 | 1 | 1 | 1 | 1 |

## 🧪 Simulation

Both Half Adder and Full Adder circuits were designed and simulated using Logisim. The simulation outputs were verified using their respective truth tables.

## 📁 Project Files

- `HALF_ADDER.circ` — Logisim Half Adder circuit
- `FULL_ADDER.circ` — Logisim Full Adder circuit

## ✅ Result

The Half Adder and Full Adder circuits were successfully designed and simulated using Logisim. The simulation outputs were verified using the corresponding truth tables.

## 👨‍💻 Author

KLH-FED-2026 — Section 9 — Batch 7
