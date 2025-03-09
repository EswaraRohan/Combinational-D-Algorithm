# Combinational D-Algorithm

## Overview

This project implements the **D-Algorithm**, a deterministic method for Automatic Test Pattern Generation (ATPG) in combinational circuits. Developed by Roth in 1966, the D-Algorithm systematically generates test vectors to detect faults in digital circuits, ensuring efficient fault coverage.

## Features

- **Fault Detection**: Identifies single stuck-at faults in combinational circuits.
- **Deterministic Approach**: Guarantees test vector generation if a fault is detectable.
- **C++ Implementation**: Utilizes Standard Template Library (STL) for efficient data handling.

## Tech Stack

- **Programming Language**: C++
- **Libraries**: Standard Template Library (STL)

## Usage

Input Specification:
Define the combinational circuit and specify the fault to be tested.
Ensure the input format aligns with the expectations outlined in the d_algorithm.cpp file.

Execution:
Run the compiled executable.
Follow on-screen prompts to input circuit details and faults.

Output:
The program will display the test vectors capable of detecting the specified faults or indicate if the fault is undetectable.


## References
Roth, J. P. (1966). Diagnosis of Automata Failures: A Calculus and a Method. IBM Journal of Research and Development.
D-Algorithm - Combinational ATPG in DFT (VLSI) - Technobyte
