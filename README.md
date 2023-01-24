_Printf()

Synopsis

This is a simple implementation of printf funcion  that is used to print a formatted string to the standard output 
(typically the console). The format string passed to printf() can include special placeholders, called conversion specifiers, 
that are replaced with the corresponding argument passed to the function. For example, printf("Hello, %s!", "world"); 
would print "Hello, world!" to the console. 
Additionally, printf() can be used to print numerical values in various formats, such as decimal, octal, or hexadecimal. 
It returns the number of characters written to the output.

Description

The _printf() function produces output according to a format which is described below. This function write its output to the stdout, the standard output stream. Returns the count of printed characters when the function is successful and -1 when the function fails.

The available convertion specifiers are:

- %c: Prints a single character.
- %s: Prints a string of characters.
- %d: Prints integers.
- %i: Prints integers.
- %b: Prints the binary representation of an unsigned decimal.
- %u: Prints unsigned integers
- %x: Prints the hexadecial representation of an unsigned decimal in lowercase letters
- %X:Prints the hexadecial representation of an unsigned decimal in uppercase letters
- %r: Prints a reversed string
- %R: Prints the Rot13 interpretation of a string

Usage
- All the files to be compiled on Ubuntu 20.04LTS
- Complie your code with `gcc -Wall -Werror -Wex -pedantic *.c`
- Include the "alx.h" header file on the functions using the _printf()
