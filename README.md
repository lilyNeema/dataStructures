# Stack Implementation in C

## Overview

This project demonstrates a simple implementation of a stack data structure using an array in the C programming language. The stack is a linear data structure that follows the Last In, First Out (LIFO) principle, meaning that the last element added is the first one to be removed.

## Features

- **Push**: Add an element to the top of the stack.
- **Pop**: Remove the top element from the stack.
- **Peek**: View the top element of the stack without removing it.
- **isEmpty**: Check if the stack is empty.
- **isFull**: Check if the stack is full.

## Program Structure

The program consists of the following components:

- **Stack Structure**: The stack is implemented using an array with a fixed maximum size (`MAX`) and an integer (`top`) to track the current top position in the stack.
- **Functions**:
  - `initialize`: Initializes the stack by setting the `top` to -1.
  - `isEmpty`: Returns 1 if the stack is empty, 0 otherwise.
  - `isFull`: Returns 1 if the stack is full, 0 otherwise.
  - `push`: Adds an element to the stack if it is not full.
  - `pop`: Removes and returns the top element from the stack if it is not empty.
  - `peek`: Returns the top element without removing it if the stack is not empty.

## Getting Started

### Prerequisites

- A C compiler (e.g., GCC)
- Basic knowledge of C programming

### Compiling the Program

To compile the program, use the following command in your terminal:

```bash
gcc stack.c -o stack
