# ft_printf

`ft_printf` is a custom implementation of the standard C function `printf`. This project was developed as part of a C programming exercise, with the goal of replicating the basic behavior of `printf`, allowing flexible formatting and display of data on the console. The function handles different data types and supports format specifiers such as `%c`, `%s`, `%d`, `%i`, `%u`, `%x`, `%X` and `%p`, among others.

This project not only reinforces key concepts such as string manipulation and data type conversion, but also introduces memory management and pointer handling in C, while respecting the restrictions imposed by the C library standard.

## Features

- Support for the most common format specifiers:
- `%c`: Character
- `%s`: Character string
- `%d` / `%i`: Signed integers
- `%u`: Unsigned integers
- `%x` / `%X`: Hexadecimal integers (lower and upper case)
- `%p`: Pointers
- `%%`: Literal percentage
- Width and precision management for formatted output.
- Support for variadic functions to handle an arbitrary number of arguments.
