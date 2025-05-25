# Go Interpreter

This project aims to create a working interpreter for a simple C-like language, written in Go.

## About

This project is based on Thorsten Ball's _[Writing An Interpreter In Go](https://interpreterbook.com/)_. By following this book, I want to learn how interpreters work under the hood and hopefully achieve enough understanding to implement such systems in any chosen language with additional features not covered in the book.

## Language Features

The interpreter will support:
- Variable declarations (`let x = 5;`)
- Functions (`fn add(a, b) { return a + b; }`)
- Basic arithmetic (`+`, `-`, `*`, `/`)
- Conditionals and control flow
- First-class functions

## Project Structure

- `token/` - Token definitions and types
- `lexer/` - Lexical analysis (tokenization)
- `parser/` - Syntax analysis (AST generation)
- `evaluator/` - Expression evaluation
- `repl/` - Read-Eval-Print Loop