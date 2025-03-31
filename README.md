# C Project 1 - ML to C Code Translator

## Project Overview

This project involves creating a program that translates a simplified version of the ML programming language into C code, compiles it, and then executes the generated program. The translator processes ML-like files that contain function definitions, variable assignments, and print statements, converting them into C code that can be executed on a Linux platform.

## Features

- **ML File Parsing**: The program reads an input file in a simplified ML-like language format and processes each line.
- **Function Translation**: It translates ML function definitions into C function declarations and generates function bodies.
- **Variable Management**: The program tracks variable declarations and ensures that variables are only declared once in the generated C code.
- **Statement Processing**: 
  - **Assignments**: Converts `identifier <- expression` into C-style assignments.
  - **Print Statements**: Converts `print expression` into a function call to print formatted values (either integers or floating-point numbers).
  - **Function Calls**: Translates ML function calls into C function calls.
- **Error Handling**: Reports errors for invalid function definitions, unknown statements, or issues during file parsing.
- **C Code Generation**: After parsing the ML file, it generates C code and writes it to a file.
- **Compilation and Execution**: The program compiles the generated C code using GCC and executes the resulting executable. It also handles optional arguments passed via the command line.

