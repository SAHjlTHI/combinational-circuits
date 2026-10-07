# Combinational Circuits using Verilog HDL

## 📌 About

This repository contains the **RTL implementation and functional verification of fundamental combinational circuits using Verilog HDL**.

The project covers basic logic gates, arithmetic circuits, multiplexers, and demultiplexers. Each circuit is implemented in Verilog and verified using a corresponding testbench.

## 📚 Circuits Covered

### 🔹 1. Logic Gates

Logic gates are the basic building blocks of digital circuits. They perform logical operations on one or more binary inputs.

Implemented gates:

* AND
* OR
* NOT
* NAND
* NOR
* XOR
* XNOR

### 🔹 2. Adders

Adders are arithmetic circuits used to perform binary addition.

* **Half Adder** – Adds two 1-bit binary inputs and produces Sum and Carry.
* **Full Adder** – Adds three 1-bit inputs, including Carry-in, and produces Sum and Carry-out.

### 🔹 3. Subtractors

Subtractors are arithmetic circuits used to perform binary subtraction.

* **Half Subtractor** – Subtracts two 1-bit inputs and produces Difference and Borrow.
* **Full Subtractor** – Performs subtraction using two input bits and Borrow-in, producing Difference and Borrow-out.

### 🔹 4. Multiplexer (MUX)

A Multiplexer is a **data selector** that selects one input from multiple input lines based on the select line(s) and forwards the selected input to the output.

Implemented:

* 2:1 MUX
* 4:1 MUX

### 🔹 5. Demultiplexer (DEMUX)

A Demultiplexer is a **data distributor** that takes a single input and routes it to one of multiple output lines based on the select line(s).

Implemented:

* 1:2 DEMUX
* 1:4 DEMUX

## 🛠️ Tools Used

* Verilog HDL
* ModelSim
* Digital Logic Design

## 📂 Repository Structure

```text
Combinational-Circuits/
│
├── Logic_Gates/
│   ├── AND/
│   ├── OR/
│   ├── NOT/
│   ├── NAND/
│   ├── NOR/
│   ├── XOR/
│   └── XNOR/
│
├── Adders/
│   ├── Half_Adder/
│   └── Full_Adder/
│
├── Subtractors/
│   ├── Half_Subtractor/
│   └── Full_Subtractor/
│
├── MUX/
│   ├── 2_to_1_MUX/
│   └── 4_to_1_MUX/
│
├── DEMUX/
│   ├── 1_to_2_DEMUX/
│   └── 1_to_4_DEMUX/
│
└── README.md
```

## ✅ Verification

Each circuit is verified using a Verilog testbench by applying different input combinations and observing the corresponding outputs.

Simulation and functional verification are performed using **ModelSim**.

## 🎯 Learning Objectives

* Understand fundamental combinational logic circuits
* Implement digital circuits using Verilog HDL
* Write and use Verilog testbenches
* Verify circuit functionality through simulation
* Understand Boolean logic, truth tables, and signal selection

## 👩‍💻 Author

**K. Sahithii**

B.Tech – Electronics and Communication Engineering

---

⭐ This repository represents my practice and learning in **Digital Electronics, Verilog HDL, and VLSI Design**.

```

**Ila short explanations chaalu.** Every circuit ki full theory README lo pedithe chala lengthy aipothundi. Individual folder lo `README.md` create chesi, for example **Full Adder → Boolean expression + truth table + working + waveform** pettadam better.
```
