<h3 align="center">42 São Paulo</h3>
<div align="center">

![License](https://img.shields.io/github/license/thiago-neves/ft_printf)
![42 São Paulo](https://img.shields.io/badge/42-SP-1E2952?color=white)
![Top language](https://img.shields.io/github/languages/top/thiago-neves/ft_printf?color=007FFF)

</div>

# 🖨 ft_printf
This project consists of coding a library that contains a simplified version of the printf function.

##  📋 Contents
- [Getting Started]()
- [Makefile commands]()
- [Available flags]()
## 🏁 Getting Started

To compile the project you just need to use the command `make` in the terminal and execute the .a file in your main function, the ft_printf function exactly as the original printf with fewer available flags (see below).

## 📝 Makefile commands

`make` compile and generates the libft.a.

`make clean` clean all the .o files from the folder.

`make fclean` executes the make clean command and remove libft.a from the folder.

`make re` executes the make clean and make commands to recompile the library.

## 🏳️ Available flags

The `%c` flag prints the corresponding character from the variable.<br>
The `%d` and `%u` prints the integer value from the variable.<br>
The `%p` flag prints the address of the variable.<br>
The `%s` flag prints the string of the pointer.<br>
The `%x` flag prints the value of the variable in hexadecimal integer.<br>
