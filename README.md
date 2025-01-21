Overview

This project implements a Pattern Generator class in SystemVerilog, which generates a sequence of numbers in steps of 10, starting from 9. The sequence stops after reaching 59, and the program displays a message indicating the end of the sequence.

Key Components

Class Definition

The pattern_generator class encapsulates the functionality for generating the sequence.

It contains:

value: An integer variable initialized to 9.

new function: A constructor to initialize the value variable.

generate_next task: Generates the next number in the sequence and prints it. If the sequence exceeds 59, it displays "End of sequence."

Testbench

The testbench (tb_pattern_generator) creates an object of the pattern_generator class and generates the sequence by calling the generate_next task in a loop using the repeat construct.
