The purpose of this file is to give instruction on how to compile the accompanying program to this assignment. 

On a system running a Linux distribution with flex, bison, make, and build-essential packages installed, perform the following steps.
1. Assure you are in the Project1-Lexer directory with the lexer.l file. 
You can verify this with the command 
>> ls
which lists the files in the current directory.
If you are not in the correct directory, enter the command 
  >>> cd <relative_path>/Project1-Lexer
  to switch, replacing relative_path with the directory you downloaded the attachment into.
2. Ensure that the source file named "source.txt" is also in this directory.
3. Enter the command >> flex lexer.l
4. Enter the command >> gcc lexer.c
5. Enter the command >> ./a.out
6. Verify the terminal output for accurate tokenification of the source code according the the frammar in the course materials
