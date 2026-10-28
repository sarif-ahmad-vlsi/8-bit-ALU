# 8-bit-ALU
Design and functional verification of an 8-bit ALU using Verilog/SystemVerilog, supporting arithmetic, logical, and shift operations with overflow detection and testbench-based corner-case verification.

# 8-Bit ALU — RTL Design & Functional Verification
## 📌 Project Overview
This project focuses on the RTL design and functional verification of an **8-bit Arithmetic Logic Unit (ALU)** using Verilog/SystemVerilog.

An ALU is a digital circuit that performs arithmetic and logical operations on input data based on a control signal. This project implements common ALU operations and verifies their functionality through simulation, including normal operating conditions and corner cases.

## 🎯 Project Objectives
- Design an 8-bit ALU using Verilog/SystemVerilog.
- Implement arithmetic, logical, and shift operations.
- Use control signals to select the required operation.
- Detect and verify arithmetic overflow conditions.
- Develop a testbench to check normal and corner-case scenarios.
- Debug and analyze simulation waveforms.

## 🛠️ Tools & Technologies
- HDL: Verilog HDL / SystemVerilog
- Simulation: Synopsys VCS,used in the project
- Waveform Debugging: Synopsys Verdi,used in the project
- Concepts: RTL Design, Combinational Logic, Functional Verification

## ⚙️ Design Features
- 8-bit input operands
- Operation selection through control signals
- Arithmetic operations
- Logical operations
- Shift operations
- Overflow detection
- Simulation-based functional checking

## 🧪 Verification Scenarios
The testbench is intended to verify:
1. Arithmetic operations with different input values
2. Logical operations and their expected results
3. Shift operations, including boundary shift amounts supported by the design
4. Zero-valued and maximum-valued operands
5. Boundary conditions for signed or unsigned arithmetic, as applicable
6. Overflow detection
7. Normal and corner-case input combinations

## 🔄 Verification Workflow
1. Write the ALU RTL module.
2. Develop a testbench to apply input operands and operation-select signals.
3. Compile and run the design using the simulation tool.
4. Compare the actual outputs against expected results.
5. Inspect waveforms to debug incorrect behavior.
6. Record the verified simulation results.

## 📁 Suggested Repository Structure
8-bit-alu-systemverilog/
├── rtl/
│   └── alu_8bit.v
├── tb/
│   └── alu_8bit_tb.sv
├── sim/
│   └── simulation.log
├── screenshots/
│   └── alu_waveform.png
└── README.md

## 📊 Simulation Results
Add the actual results after running your testbench.
| Verification item | Result |
| Arithmetic operations | Add verified result |
| Logical operations | Add verified result |
| Shift operations | Add verified result |
| Overflow detection | Add verified result |
| Corner-case scenarios | Add verified result |

## 📚 Key Learnings
- Combinational RTL design
- Arithmetic and logical circuit implementation
- Control-signal-based operation selection
- Overflow detection
- Testbench development and functional verification
- Simulation waveform debugging

## 👨‍💻 Author
Sarif Ahmad
M.Tech — Electronic Circuits and System Design  
Aligarh Muslim University (AMU)

- LinkedIn: https://www.linkedin.com/in/ahmad-a-68b500138/
- GitHub: https://github.com/sarif-ahmad-vlsi

This project demonstrates practical learning in digital design and functional verification for VLSI applications.
