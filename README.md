# Two-Pass Assembler

## Overview
This project implements a two-pass assembler for an assembly language. The assembler works in two phases: the first pass generates a symbol table and an operation table (OPTAB), and the second pass uses these tables to translate assembly code into machine code.

## Features
- **First Pass**: Scans the source code to build a symbol table, which maps symbolic labels to their corresponding addresses. It also constructs an OPTAB for mnemonic operation codes to their machine code equivalents.
- **Second Pass**: Uses the symbol table and OPTAB to convert the assembly instructions into machine code or object code.

## How to Use

- **Ensure you have a C compiler installed on your system (like gcc).
- **Compile the assembler.c file using the C compiler:
gcc -o assembler assembler.c
- **Run the compiled program with the input file:
./assembler
The program expects an input.asm file (in the same directory).
