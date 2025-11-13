# Nand2Tetris Implementation

## Overview
This repository contains my implementation of the **Nand2Tetris course** (The Elements of Computing Systems), building a computer from first principles — from logic gates to assembler and beyond. The work demonstrates both hardware design and software development, progressing through the course projects.

The repository is divided into two parts:

- **Part I: Hardware** – designing and implementing the Hack computer hardware.
- **Part II: Software** – virtual machine, high-level language (Jack), compiler, and operating system.

Details of the projects and their implementation can be found in *The Elements of Computing Systems* by Nisan and Schocken.

---

## Current Progress

### Part I: Hardware
Completed projects:

1. **Project 01: Boolean Logic** – implementation of basic logic gates and combinational circuits.  
2. **Project 02: Boolean Arithmetic** – adders, ALU, and arithmetic logic circuits.  
3. **Project 03: Sequential Logic** – flip-flops, registers, counters, and memory elements.  
4. **Project 04: Machine Language** – CPU design and instruction implementation.  

Work in progress:

5. **Project 05: Computer Architecture** – integration of CPU, memory, and I/O modules into a working Hack computer.

Upcoming:

6. **Project 06: Assembler** – Python-based assembler to translate Hack assembly code into machine code.

### Part II: Software
Future projects (planned):

7. **Project 07: Virtual Machine, Stack Arithmetic**  
8. **Project 08: Virtual Machine, Program Control**  
9. **Project 09: High-Level Language (Jack)**  
10. **Project 10: Compiler, Syntax Analysis**  
11. **Project 11: Compiler, Code Generation**  
12.Operating System.

---

---

## Technical Highlights
- Hardware modules implemented in a version of HDL specified in the textbook using the Nand2Tetris simulator.  
- CPU, ALU, memory, and sequential logic designed from scratch.  
- Assembler (Project 06) planned to parse symbolic Hack assembly and generate binary machine code.  
- All projects follow the exercises and specifications provided in *The Elements of Computing Systems*.

---

## Usage
Hardware projects can be tested using the **Nand2Tetris Hardware Simulator**.  which is run via a bash script found in tools jdk will be needed to run the script.
Assembler (Project 06) will run as a Python script.

## Future Extensions and TODO
Beyond the course material, I plan to extend the Hack computer with the following projects:

- Networking Layer – enabling the Hack computer to connect to the internet and communicate with other machines.

- Self-hosted Elements of Computing – implement a basic reader or viewer on the Hack machine to read portions of The Elements of Computing Systems natively.

- Optimizations and Automation – improve assembler and VM performance, and create scripts to automate project tests.

- These extensions aim to push the Hack computer beyond the course exercises and explore advanced systems programming concepts.

