# Project: [Module Name]  
**Category**: [e.g., Combinational Logic / Sequential Logic / FSM]  
**Level**: [Beginner / Intermediate / Advanced]  

---

## 🧠 Overview

Brief description of what this module does and its purpose.

**Example**:  
This is a 4-bit Ripple Carry Adder that takes two 4-bit binary inputs and computes their sum using a cascade of full adder modules. It includes carry-in and carry-out ports.

---

## 🔧 Features

- [x] RTL module with parameterized bit-width
- [x] Simple testbench with multiple test vectors
- [x] Waveform visualization support
- [x] Modular design (e.g., submodules like full_adder)

---

## 📁 File Structure

| File | Description |
|------|-------------|
| `adder.v` | RTL design of the ripple carry adder |
| `full_adder.v` | 1-bit full adder submodule |
| `tb_adder.v` | Testbench for verifying functionality |
| `waveform.gtkw` | GTKWave config file for waveform viewing |
| `README.md` | This documentation file |

---

## 📷 Waveform Screenshot

*(Optional: insert GTKWave screenshot image)*  
![Waveform](waveform.png)

---

## 🧪 Testbench Summary

- Written in SystemVerilog
- Uses `$display` and `$monitor` for debug
- Includes corner cases: overflow, carry propagation, zero inputs

---

## 🚀 How to Run

### 1. Compile

```bash
iverilog -o adder_tb tb_adder.v adder.v full_adder.v

