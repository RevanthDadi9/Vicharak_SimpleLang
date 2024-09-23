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
- **Example**:let a = 5;
               let b = 10;


### 3. Arithmetic Operations
- **Supported Operators**: `+`, `-`,`*`,`&`,`|`
- **Example**: `a = b + c;`

## Example Program
```plaintext
let a = 5;
let b = 10;
c = a + b;
d = a * b;
e = a & b;
f = a | b;

// Conditional 
if (c == 30) { 
    c = c + 1; 
}

