<h1 align="center">📄 FT_PRINTF</h1>

<p align="center">
  <strong>Custom printf Implementation — 42 School</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black"/>
  <img src="https://img.shields.io/badge/42-000000?style=for-the-badge&logo=42&logoColor=white"/>
</p>

---

## About

A custom re-implementation of the C `printf()` function. Handles variadic arguments and multiple format specifiers with proper memory management.

## Supported Conversions

| Specifier | Description |
|-----------|-------------|
| `%c` | Print a single character |
| `%s` | Print a string |
| `%p` | Print a pointer address in hexadecimal |
| `%d` / `%i` | Print a signed decimal integer |
| `%u` | Print an unsigned decimal integer |
| `%x` / `%X` | Print a number in lowercase/uppercase hexadecimal |
| `%%` | Print a literal percent sign |

## Usage

```bash
make
```

```c
#include "ft_printf.h"

int main(void)
{
    ft_printf("Hello %s! You are %d years old.\n", "World", 42);
    ft_printf("Address: %p\n", &main);
    ft_printf("Hex: %x | %X\n", 255, 255);
    return (0);
}
```

---

<p align="center"><sub>42 School · Common Core · Variadic functions</sub></p>
