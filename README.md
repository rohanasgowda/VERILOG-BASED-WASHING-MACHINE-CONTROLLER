# Verilog-Based Washing Machine Controller

[![Verilog](https://img.shields.io/badge/Language-Verilog-orange.svg)](https://en.wikipedia.org/wiki/Verilog)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/Status-Completed-success)](#)

## 📌 Overview
This project implements a **Washing Machine Controller** using **Verilog HDL**. The system simulates the washing process including water fill, wash, rinse, and spin cycles. It is designed for FPGA implementation and demonstrates sequential control using **finite state machines (FSM)**.

## 📂 Repository Structure

| File | Description |
| :--- | :--- |
| `washing_machine.v` | **Core Design:** The primary RTL logic and FSM implementation. |
| `washing_machine_tb.v` | **Testbench:** Comprehensive simulation suite for verification. |
| `RTL_Schematic.png` | Architectural visualization of the synthesized logic gates. |
| `state_diagram.png` | Logical flow showing transitions between FSM states. |
| `waveform.png` | Timing diagrams confirming cycle durations and signal integrity. |

---

## 🧩 Components / Tools Used
* **Verilog HDL**
* **FPGA/Simulator** (ModelSim, Vivado, or equivalent)
* **Testbench files** for simulation

## ⚙️ Features
* **Water Fill Cycle:** Fills the tank to a predefined level.
* **Wash Cycle:** Simulates washing action for a set duration.
* **Rinse Cycle:** Drains and refills water for rinsing clothes.
* **Spin Cycle:** Activates motor for drying clothes.
* **User Inputs:** Start, Stop, and Reset controls.
* **Display Outputs:** LEDs or 7-segment display to indicate current cycle.

## ✅ Applications
* FPGA/HDL learning and demonstration
* Embedded system design projects
* Sequential control system examples

---
**Developed by [rohanasgowda](https://github.com/rohanasgowda)**
