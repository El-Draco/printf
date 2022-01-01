# **printf**

## A simple function that mimicks the real printf with standard format specifiers - %cspdiuxX using variadic arguments in C
---
## Function  prototype is as follows (same as libc printf):
```c++
int ft_printf(const char *, ...);
```
___

## A small description of the supported format specifiers:
```c++
    "%c" // print a single character.
    "%s" // a string of characters
    "%p" // The void * pointer argument is printed in hexadecimal.
    "%d" // print a decimal (base 10) number.
    "%i" // print an integer in base 10.
    "%u" // print an unsigned decimal (base 10) number.
    "%x" // print a number in hexadecimal (base 16), with lowercase.
    "%X" // print a number in hexadecimal (base 16), with uppercase.
    "%%" // print a percent sign
```

>Note: I did not implement buffer managament in this version :D