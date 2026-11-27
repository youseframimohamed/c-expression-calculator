# Software Design

## 1. Architecture Overview

The C Expression Calculator follows a modular design consisting of three main stages:

- Tokenisation
- Parsing
- Evaluation

Each stage has a clearly defined responsibility.

## 2. System Architecture

```text
       USER INPUT
            |
            v
        TOKENIZER
            |
            v
       TOKEN ARRAY
            |
            v
          PARSER
            |
            v
        EVALUATION
            |
            v
       FINAL RESULT
```

## 3. Component Responsibilities

### Tokeniser

The tokeniser reads the input expression and converts it into a sequence of tokens.

It recognises:
- Numbers
- Arithmetic operators
- Opening parentheses
- Closing parentheses

### Parser

The parser processes the tokens and checks whether the expression follows the expected grammatical rules.

It is responsible for:
- Checking expression structure.
- Enforcing operator precedence.
- Handling parentheses.
- Detecting syntax errors.

### Evaluator

The evaluation stage calculates the expression's value.

It must handle arithmetic errors, including division by zero.

## 4. Data Flow Example

Input:

```text
3 + 4 * (2 - 1)
```

The tokeniser converts the input into tokens.

The parser processes the tokens whilst respecting mathematical precedence.

The evaluator calculates the final result.

Output:

```text
7
```

## 5. Design Principles

- Separation of responsibilities.
- Modular code organisation.
- Clear error handling.
- Readable and maintainable code.
- Reliable expression evaluation.
