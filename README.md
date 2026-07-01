# 8 Bit Full Custom ALU Design VLSI
**Hacettepe University - ELE419 Integrated Circuit Design Term Project**

This repository contains the layout design of an 8 Bit Custom ALU which has shifting and multiply operations. The main performance criterion was area so all of the performance optimization done to reduce used semiconductor wafer surface. All of the work done by owner of the repository.

## Project Overview
- Bit sliced 8 Bit Aritmetic and Logic blocks which contains ripple carry adder, and, or, nand, nor, not and xor gates.
- N,V,Z,C flag generation block that supports comparion operation: less, greater and equal.
- Mux tree for shift operations like aritmetic and logic shift left or right.
- 8x8 multiplier 7 ripple carry adder but half/full adder blockwised placed in layout.
- All block are and gated which performing buffering, preventing dynamic power consumption unused operation and local input signal inversion.
- A control block which produces and gate enable and needed control signal according to opcode signals.
- A output mux which select from aritmetic, logic, multiplier or shifter block. 


## Files
- `Project.jelib`: Library of project whch contains layouts.
- `Ltspice Test`: File that contains all of the LtSpice test result.
- `LTspice Test Code Templates.txt`: All of the spice codes for layouts' and schematics' verification of the project.
