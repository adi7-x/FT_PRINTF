# ft_printf - 42 School Project

## Overview
The `ft_printf` project at 42 school is a custom implementation of the standard C `printf` function. It focuses on mastering variadic functions in C and understanding how formatted output works.

## Features
Supported conversions:
- `%c` : Single character
- - `%s` : String
  - - `%p` : Pointer address
    - - `%d` / `%i` : Signed decimal integer
      - - `%u` : Unsigned decimal integer
        - - `%x` / `%X` : Hexadecimal (lowercase/uppercase)
          - - `%%` : Percent sign
           
            - ## Usage
            - To compile the library, run:
            - ```bash
              make
              ```
              This will create `libftprintf.a`. You can then include the header `ft_printf.h` and link the library with your project.
              
