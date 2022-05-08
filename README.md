 printf ()
The printf project is a collaboration between Muhammad-ahid Abdulsalam and Balogun Azeez, actual students of Software Engineering at Holberton School (ALX), where a function named "_printf" imitates the actual "printf" command located in the stdio.h library. It contains some of the basic features and functions found in the manual 3 of "printf".
_printf() is a function that performs formatted output conversion and print data. Its prototype is the following:
int _printf(const char *format, ...)
Where format contains the string that is printed. As _printf() is variadic function, it can receive n arguments that can be replaced by n tags written inside the string.
The format tag's prototype is the following:
%[flags][length]specifier
If the program runs successfully, the return value is the amount of chars printed.
Specifier	Output
c	Character
d or i	Signed decimal integer
s	String of characters
b	Signed binary
o	Signed octal
u	Unsigned integer
x	Unsigned hexadecimal
X	Unsigned hexadecimal (uppercase)
p	Pointer address
r	Reverse string of characters
R	ROT13 translation of string
S	String with special chars replaced by their ASCII value
%	Character

