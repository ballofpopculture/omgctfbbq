Enumeration and Exploitation
===============

* Can you see the source code?
* Can you decompile and see the source code? (.pyc and some Java files, for example)
* Do you need to write additional code?
* Is it an ELF binary? (unix command: file [filename])

Source Code Challenges
-----------------------
[example 1](https://github.com/ballofpopculture/omgctfbbq/blob/main/codebits/crackme.py)
Usually the mode straightforward of the E&E challenges. Generally the code does something simple (asks for a password, then outputs "correct" when the password has been entered, for example). 

Things to look for
* ORD conversion or its equivalent.
* Numbers that can be converted to characters (Small hex values, ASCII numbers - 0-127, traditionally)
* Code comments: Did the developer give you a big hint?
* Can you cause a buffer overload - Usually happenes in .c code where you have to set memory size for variables. 
* * Is the input assigned to a variable with a set size? 


Writing New Code
-----------------------
[example 1]()
Sometimes you're given the source code, but something is missing. Normally, code comments or an empty function will guide you as to what you need to do. 


ELF or equivalent
-----------------------
[example 1]()
Ghidra is your starting point here. 

Tactics
* Try running the program. Is it asking for input? Can you brute force a buffer overflow? 
* In Ghidra: Look for the main() function. Does anything stick out here?
* In Ghidra: Are variables being set anywhere? Perhaps one character at a time?
