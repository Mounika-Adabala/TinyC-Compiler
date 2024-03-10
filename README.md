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

# SLY: Python Library for Parsers and Compilers

SLY is a Python library designed for writing parsers and compilers, loosely based on the traditional compiler construction tools lex and yacc. It implements the LALR(1) parsing algorithm, allowing users to build custom language processors for various purposes, including configuration file parsers, domain-specific languages (DSLs), or even full programming languages.

## Features

1. **Lexers**: SLY enables the definition of lexical analyzers (tokenizers) using Python classes and methods. Lexers break down input text into tokens, which serve as the building blocks for parsing.

2. **Parsers**: SLY supports the creation of parsers with a Pythonic syntax. Users can define grammars and production rules directly in Python code.

3. **Error Handling**: SLY provides error-handling mechanisms to gracefully manage parsing errors and offer informative error messages.

4. **Open Source**: SLY is an open-source project, allowing anyone to use, modify, and contribute to its Python library for free.

## Installation

To utilize SLY, you need to install the library using pip:

```bash
pip install sly
```
SLY provides two separate classes `Lexer` and `Parser`. The `Lexer` class is used to break input text into a collection of tokens specified by a collection of regular expression rules. The `Parser` class is used to recognize language syntax specified in the form of a context-free grammar. These two classes are typically used together to create a parser.

Lexers must specify a token set that defines all possible token type names that can be produced by the lexer. A parser is responsible for understanding the syntax and structure of the input language.

You define a parser by creating a class and using decorators to specify the grammar rules.

YACC (Yet Another Compiler Compiler) is a tool used in the field of compiler construction and formal language processing. It acts as a code generator, taking a formal grammar description of a programming language and producing a parser for that language. The generated parser typically uses a parsing technique called LALR (Look-Ahead Left-to-Right Rightmost Derivation).
