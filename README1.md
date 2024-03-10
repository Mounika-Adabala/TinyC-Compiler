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

