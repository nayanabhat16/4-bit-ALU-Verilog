# 4-bit Arithmetic Logic Unit (ALU) using Verilog HDL

## 1. Introduction
An Arithmetic Logic Unit (ALU) is an important component of a digital processor. It performs arithmetic and logical operations on binary data.

This project implements a simple 4-bit ALU using Verilog HDL.

## 2. Objectives
- To design a 4-bit ALU using Verilog.
- To implement arithmetic and logical operations.
- To understand combinational logic design.
- To verify the design through simulation.

## 3. Operations Performed

| Select | Operation |
|---|---|
| 000 | Addition |
| 001 | Subtraction |
| 010 | AND |
| 011 | OR |
| 100 | XOR |
| 101 | NOT A |
| 110 | Left Shift |
| 111 | Right Shift |

## 4. Tools Used
- Verilog HDL
- EDA Playground
- Icarus Verilog 12.0
- EPWave

## 5. Design Description
The ALU takes two 4-bit inputs, A and B, and a 3-bit selection signal. Based on the selection signal, it performs the required operation and produces a 4-bit result.

A carry output is provided for addition.

## 6. Simulation and Verification
The design was simulated using Icarus Verilog.

All eight operations were tested successfully. Carry generation was also verified using the inputs 1111 and 0001.

## 7. Expected Applications
- Digital processors
- Microcontrollers
- Arithmetic circuits
- Digital system design

## 8. Conclusion
A simple 4-bit ALU was successfully designed and simulated using Verilog HDL. This project provided practical understanding of combinational logic, Verilog coding, testbench development and waveform analysis.
