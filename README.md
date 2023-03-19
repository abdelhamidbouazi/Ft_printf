# ft_printf

An implementation of the printf function in C, designed to be lightweight and customizable. Supports the basic format specifiers, as well as additional flags and modifiers. Made with pure C, without external libraries or dependencies.

## Features

- Supports the basic format specifiers: `%d`, `%i`, `%u`, `%o`, `%x`, `%X`, `%f`, `%c`, `%s`, `%%`
- Additional flags and modifiers for more flexibility
- Supports output to stdout, file streams, and dynamically allocated strings
- Lightweight and customizable implementation, with no external dependencies

## Usage

To use the ft_printf function, simply include the header file `ft_printf.h` and call the function with the desired format string and arguments. The function returns the number of characters printed (excluding the null terminator), or a negative value if an error occurred.

## Examples

```c
#include "ft_printf.h"

int main(void) {
    ft_printf("Hello, %s!\n", "world");
    ft_printf("Integer: %d\n", 42);
    ft_printf("Hexadecimal: %x\n", 0x1234abcd);
    return 0;
    
}
```

## Contributing

Contributions and bug reports are welcome! Please open an issue or submit a pull request.

