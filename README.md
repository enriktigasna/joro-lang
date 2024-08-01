
# Joro Programming Language

A fully procedural tree-walking interpreted language written in rust.


## Usage/Examples

```
fn fib(n) {
    if (n) >= 2 {
        return fib((n) - 1) + fib((n) - 2);
    };
    if (n) < 2 {
        return n;
    };
}

fn main() {
    let n = int(input("Which entry in the fibbonaci sequence do you want? "));
    print(fib(n));
}
```
## Features

- Procedural design
- Dynamic typing
- AST-based interpretation of programs
- Scope-aware symbol table
- C-like syntax
- Extensible design to add new language Features
- 12 Operators
- Recursive expressions
- Support for functional recursion
## Builtin functions

### print(args..)
Prints the given arguments to the console, followed by a newline. Returns 0 after a successful print.

### input(prompt...)
Prompts the user for input and returns the entered string.

### str(args...)
Converts the given arguments to a string representation.

### int(args..)
Converts the given arguments to an integer.
