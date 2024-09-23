# Vicharak_SimpleLang# 8-Bit Compiler

## Introduction
The 8-Bit Compiler is a simple compiler designed to translate a minimalistic high-level programming language into assembly code for an 8-bit CPU. This project serves as an educational tool to understand compiler construction and 8-bit architecture.

## Features
- **Lexical Analysis**: Tokenizes source code written in the high-level language.
- **Parsing**: Constructs an Abstract Syntax Tree (AST) from the tokens.
- **Code Generation**: Produces assembly code compatible with the 8-bit CPU.
- **Basic Constructs**: Supports variable declarations, assignments, arithmetic operations, and conditional statements.

## Language Constructs

### 1. Variable Declaration
- **Syntax**: `int <variable_name>;`
- **Example**: `int a;`

### 2. Assignment
- **Syntax**: `<variable_name> = <expression>;`
- **Example**: `a = b + c;`

### 3. Arithmetic Operations
- **Supported Operators**: `+`, `-`
- **Example**: `a = b - c;`

### 4. Conditionals
- **Syntax**: `if (<condition>) { <statements> }`
- **Example**: `if (a == b) { a = a + 1; }`

## Example Program
```plaintext
// Variable declaration 
int a;
int b; 
int c; 

// Assignment 
a = 10; 
b = 20; 
c = a + b; 

// Conditional 
if (c == 30) { 
    c = c + 1; 
}

