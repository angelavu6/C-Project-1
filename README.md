# Java-Project-1
**Student:** My Phuong Vu  
**Platform:** Linux  

This project involves processing a custom ML program and converting it into a C program that can be compiled and executed. The main functionality includes:

- **Parsing ML Program:** The program reads a specified ML file, processes its content, and generates corresponding C code.
- **Function Handling:** Functions in the ML file are parsed and converted into C function definitions. The program handles function parameters, variable declarations, assignments, and return statements.
- **Variable Declaration:** Variables are dynamically declared in the C code only if they are used but not declared yet, ensuring no duplicate variable declarations.
- **Formatted Output:** The program implements a custom `print_formatted` function that prints values either as integers or floating-point numbers, depending on their type.
- **Error Handling:** It includes robust error handling for file reading, function definition parsing, and syntax checking.
- **Compilation and Execution:** The generated C code is compiled using the GCC compiler and executed. If successful, the program displays the output, and all intermediate files are cleaned up.

This project demonstrates key skills in file manipulation, string processing, C programming, and system-level programming under a Linux environment.
