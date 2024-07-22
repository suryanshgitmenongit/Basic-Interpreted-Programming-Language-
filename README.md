# Basic-Interpreted-Programming-Language
Documentation:

Here's a detailed Markdown documentation for the "Poverty Interpreter" language:

```markdown
# Poverty Interpreter

## Table of Contents
1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Language Basics](#language-basics)
   - [Variables](#variables)
   - [Data Types](#data-types)
   - [Operators](#operators)
4. [Control Structures](#control-structures)
   - [If-Else Statements](#if-else-statements)
   - [While Loops](#while-loops)
   - [For Loops](#for-loops)
5. [Built-in Functions](#built-in-functions)
6. [Error Handling](#error-handling)
7. [Examples](#examples)
8. [Contributing](#contributing)
9. [License](#license)

## Introduction

Poverty Interpreter is a minimalist programming language designed for educational purposes. It offers basic programming constructs while maintaining a simple syntax, making it ideal for beginners or for demonstrating language implementation concepts.

## Installation

To use Poverty Interpreter, ensure you have Python 3.6+ installed. Then follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/poverty-interpreter.git
   ```
2. Navigate to the project directory:
   ```
   cd poverty-interpreter
   ```
3. Run the interpreter:
   ```
   python poverty_interpreter.py
   ```

## Language Basics

### Variables

Variables are declared using the `let` keyword:

```
let x = 5
let y = 3.14
let name = "John"
```

### Data Types

Poverty Interpreter supports the following data types:
- Integers
- Floats
- Booleans (`true` and `false`)

### Operators

- Arithmetic: `+`, `-`, `*`, `/`
- Comparison: `<`, `>`, `<=`, `>=`, `==`
- Logical: `and`, `or`, `not`

## Control Structures

### If-Else Statements

```
if x > 5 do
    let y = 10
else
    let y = 5
```

### While Loops

```
while x < 10 do
    let x = x + 1
```

### For Loops

```
for let i = 0; i < 5; let i = i + 1 do
    let x = x + i
```

## Built-in Functions

Currently, Poverty Interpreter does not support user-defined functions. All operations are performed using the built-in operators and control structures.

## Error Handling

Poverty Interpreter provides basic error messages for common issues:
- Syntax errors
- Undefined variables
- Type mismatches
- Division by zero



