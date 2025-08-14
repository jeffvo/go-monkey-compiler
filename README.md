# Go Monkey Compiler

The `go-monkey-compiler` is an implementation of the Monkey programming language, written in Go. It includes a lexer, parser, evaluator, compiler, and virtual machine (VM). This project is designed to demonstrate the inner workings of a programming language and its execution pipeline.

## Features

- **Lexer**: Tokenizes the Monkey source code.
- **Parser**: Converts tokens into an Abstract Syntax Tree (AST).
- **Evaluator**: Interprets and evaluates the AST directly.
- **Compiler**: Compiles the AST into bytecode.
- **Virtual Machine (VM)**: Executes the compiled bytecode.

## Project Structure

The project is organized into the following directories:

- `ast/`: Contains the Abstract Syntax Tree (AST) implementation.
- `benchmark/`: Includes benchmarking tools to compare the performance of the evaluator and VM.
- `code/`: Handles bytecode generation and manipulation.
- `compiler/`: Implements the compiler for the Monkey language.
- `evaluator/`: Contains the evaluator for interpreting the AST.
- `lexer/`: Implements the lexer for tokenizing Monkey source code.
- `object/`: Defines the object system for the Monkey language.
- `parser/`: Implements the parser for generating the AST.
- `repl/`: Provides a Read-Eval-Print Loop (REPL) for interactive use.
- `token/`: Defines the tokens used by the lexer and parser.
- `vm/`: Implements the virtual machine for executing bytecode.

## Getting Started

### Prerequisites

- Go 1.20 or later installed on your system.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/jeffvo/go-monkey-compiler.git
   cd go-monkey-compiler
   ```

## credit

This is written as a follow along of the book [Writing an Compiler in Go](https://compilerbook.com/)
