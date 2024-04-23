# CPPAUTO


## Introduction

This repository contains a simple C++ code example demonstrating the usage of the `auto` keyword. The `auto` keyword allows the compiler to automatically deduce the data type of a variable based on its initializer.

## Usage

1. Compile the code using a C++ compiler.
2. Run the compiled executable to observe the output.
3. The output displays the size and type information of each `auto` variable.


## Code Description

1. **cppauto.cpp**: This file contains the main code demonstrating the usage of the `auto` keyword.
2. The `main` function initializes several variables using the `auto` keyword, each with different types.
3. The variables are named `autoBuffer0` through `autoBuffer7`, and their values are initialized with various literals and function calls.
4. The `pvfunction` function is declared to return a `void` pointer and is used to initialize `autoBuffer7`.
5. An inline function `autoBuffer8` is declared within the `main` function. This is an inline function declaration, which may or may not be used depending on the context of the program.
6. Each `auto` variable is then printed along with its size (obtained using `sizeof`) and its type (obtained using `typeid`).

## Example Output


```cpp
auto Buffer 0 size:  1,  Its Type: c
auto Buffer 1 size:  4,  Its Type: i
auto Buffer 2 size:  8,  Its Type: x
auto Buffer 3 size:  1,  Its Type: b
auto Buffer 4 size:  4,  Its Type: j
auto Buffer 5 size:  8,  Its Type: d
auto Buffer 6 size:  4,  Its Type: f
auto Buffer 7 size:  8,  Its Type: Pv
auto Buffer 8 size:  1,  Its Type: FvvE

```
