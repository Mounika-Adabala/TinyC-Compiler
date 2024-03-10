# TinyC Programming Language

TinyC is a subset of the C programming language, designed to be a simple procedural language. Its syntax closely resembles C, offering various features outlined below:

## Structure of TinyC

### 1. Global Declarations

Every TinyC program may include optional global declarations. Global variables are declared outside of any function scope, making them accessible to all functions within the program. They retain their values between function calls, facilitating information sharing across multiple functions.

### 2. Functions

A TinyC program may consist of one or more functions. The `main` function serves as the entry point, executing the entire program. Function bodies comprise zero or more statements, detailing the function's behavior. Statements can include arithmetic operations, control flow structures, or any other valid constructs.

## Features of TinyC

### 1. Procedural Language

TinyC is a procedural language, organized around procedures and functions. Procedures are named blocks of code that may take parameters, while functions are similar but return a value after computation, taking inputs and producing an output.

### 2. Statically Typed

TinyC is statically typed, meaning variable data types must be known at compilation time and cannot change during runtime.

### 3. Set of Data Types

Basic data types supported by TinyC include integers (`int`), floating-point numbers (`float`), and characters (`char`). These data types determine the kind of values variables can hold.

### 4. Set of Operators

TinyC includes various operators such as arithmetic operators (`+`, `-`, `*`, `/`), relational operators (`==`, `!=`, `<`, `>`), ternary operator (`? :`), and type casting operator.

### 5. Set of Control Flow Statements

TinyC supports conditional statements such as `if`, `else`, and `if-else`, as well as loops like `for`, `while`, and `do-while`.

### 6. Single-Line Comment

TinyC allows single-line comments for explanatory notes. Comments are typically ignored during compilation and serve as aids for programmers. They are denoted by `//`.

### 7. Limited I/O Support

TinyC offers limited I/O support, primarily focusing on output operations. The primary output mechanism is through the `print` operation, enabling the display of information to the user.


