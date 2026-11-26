Project Requirements

1. Project Overview

The C Expression Calculator is a command-line application developed in C. Its purpose is to evaluate mathematical expressions entered by the user whilst respecting standard mathematical conventions.

The application will use a structured approach to processing expressions, separating tokenisation, parsing and evaluation into distinct stages.

2. Supported Operations

The calculator shall support the following arithmetic operations:

Addition (+)

Subtraction (-)

Multiplication (*)

Division (/)

The application shall also support positive and negative numerical values.

3. Operator Precedence

The calculator must follow the standard order of mathematical operations:

Parentheses must be evaluated first.

Multiplication and division must take precedence over addition and subtraction.

Operators with equal precedence must be evaluated from left to right.

For example:

Expression:

3 + 4 * 2

Expected result:

11

4. Parentheses

The application must recognise and correctly evaluate expressions enclosed in parentheses.

Nested parentheses must also be supported.

For example:

Expression:

(3 + 4) * 2

Expected result:

14

5. Input Validation and Error Handling

The application must validate user input and handle errors gracefully without terminating unexpectedly.

The following error conditions must be detected:

Division by zero.

Invalid characters or unrecognised tokens.

Unmatched opening or closing parentheses.

Invalid or incomplete mathematical expressions.

Empty input.

Where an error occurs, the application must display a meaningful error message.

6. Input and Output

The application shall:

Accept a mathematical expression from the user.

Process and evaluate the expression.

Display the calculated result.

Report errors clearly when an expression cannot be evaluated.

7. Technical Requirements

The project shall meet the following technical requirements:

Programming language: C.

Compiler: GCC.

Application type: Command-line interface (CLI).

Modular code structure with separate source and header files.

A dedicated testing suite.

A Makefile to automate compilation and testing.

8. Project Objectives

The primary objective is to develop a reliable and well-structured expression calculator whilst demonstrating an understanding of fundamental programming and software engineering concepts.

The project aims to demonstrate:

Tokenisation and lexical analysis.

Recursive descent parsing.

Mathematical operator precedence.

Expression evaluation.

Input validation and error handling.

Modular software design.

Unit testing and build automation.

9. Scope and Limitations

The initial version will focus on basic arithmetic operations and parentheses.

Advanced mathematical functions, variables and scientific operations are outside the scope of the initial release.
