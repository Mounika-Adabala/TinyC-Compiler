TinyC is a subset of the C programming language. It is a simple procedural language. Its syntax looks similar to C language.It gives different features useful for educational purposes.
#Structure of TinyC:-
1.Global declarations:
Every TinyC program has optional global declarations.Global variables in TinyC are declared outside of any function.They are accessible to all functions within the program. Global variables retain their values between
function calls, making them useful for storing information that needs to be
shared across multiple functions.
2.Functions:
A program in tinyC may consist of one or more functions. There will be a function in every program called main which is the entry point of a program which executes the whole program. Function body consists of zero or more statements and gives details of the function. The statements can be of arithmetic,control flow or of anything
Features of TinyC:-
1.Procedural Language:
TinyC is a procedural language as it is organized of procedures and
functions.Procedures are defined with a name and take parameters.
Functions are similar to procedures but return a value after
computation.They take inputs and produce an output.
2.Statically typed:
TinyC is a statically typed programming language.in this, the data
type of a variable must be known at the time of compilation and cannot
change during runtime.
3.Set of data types:
TinyC supports basic data types like integers (int) and floating-point
numbers (float),character(char).These data types define the kind of values
variables can hold.
4.Set of Operators:
Contains various operators such as Arithmetic operators (+,-,*,/),
relational operators(==,!=,<,>),ternary operators(?,:),type casting operator.
5.Set of control flow statements:
TinyC contains conditional statements such as if,else,if-else and
loops such as for loop,while loop,do-while loop.
6.Single-line comment:
TinyC programs can include comments for explanatory notes.
Comments are usually ignored during compilation and are used to
understand for programmers.Comments are represented using //.
7.Limited I/O support:
In terms of I/O (Input/Output), tinyC offers limited support, primarily
focusing on output operations. The primary output support is through the
print operation, allowing the display of information to the user.
Implementation of TinyC:-
For compilation,a compiler is necessary for tinyC which takes the
TinyC program as an input and converts it to a valid assembly language
code.SPIM is used to test the generated assembly language code.
Compilation follows the following order:
Lexical analysis -> Syntax Analysis -> Semantic Analysis -> Intermediate
code generation -> Code Optimization -> Code generation
Interpretation follows the following order:
Lexical analysis -> Syntax Analysis -> Semantic Analysis -> Evaluate
statements.
Translation vs Evaluation:-
TinyC programs are typically translated into assembly language for
execution, emphasizing the importance of compiler design concepts. This
stands in contrast to interpretation, where programs are directly evaluated
without intermediate code generation.
