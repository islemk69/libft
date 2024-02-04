# Libft - 42 School Project

The `libft` project is a fundamental part of the 42 school curriculum, aimed at building a comprehensive C library that includes a variety of essential functions for various programming tasks.

## Features

- Over 60 standard C functions implemented (e.g., `memcpy`, `memset`, `strdup`, `atoi`, etc.).
- Functions for linked list management (e.g., `ft_lstnew`, `ft_lstadd_front`, `ft_lstmap`, etc.).
- String manipulation functions (e.g., `ft_strlen`, `ft_strcpy`, `ft_strjoin`, etc.).
- Memory management functions (e.g., `ft_memalloc`, `ft_memdel`, etc.).
- And much more.

## Getting Started

1. Clone this repository to your workspace.
2. Include the `libft.a` library in your projects.
3. Make sure to include the `libft.h` header file in your source files.
4. Compile your projects with `libft` using your preferred compiler (e.g., gcc).

## Usage Example

```c
#include "libft.h"

int main() {
    char *str = "Hello, Libft!";
    int len = ft_strlen(str);
    ft_putstr("Length of str: ");
    ft_putnbr(len);
    return 0;
}
