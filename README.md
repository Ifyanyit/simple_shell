Readme file for simple shell.

0x16. C - Simple Shell
In this repository you will find the entire project where we built our own version of a Shell.
Resources.
Read or watch:
Unix shell

Thompson shell

Ken Thompson

Everything you need to know to start coding your own shell

Additional materials:
Tutorial - Write a Shell in C

How Does the Shell Command ls Work

Learning Objectives 💡
What you should learn from this project:

Who designed and implemented the original Unix operating system

What are the three prototypes of main.

How does the shell use the PATH to find the programs.

How to execute another program with the execve system call.

How to suspend the execution of a process until one of its children terminates.

What is EOF / “end-of-file”?

Tasks ⚒️
README, man, AUTHORS

Write a README, Write a man for your shell. You should have an AUTHORS file at the root of your repository, listing all individuals having contributed content to the repository.
Betty
Write a beautiful code that passes the Betty checks.
Simple shell 0.1
Write a UNIX command line interpreter.
Simple shell 0.2
Handle command lines with arguments.
Simple shell 0.3
Handle the PATH

fork must not be called if the command doesn’t exist.

Simple shell 0.4
Implement the exit built-in, that exits the shell

Usage: `exit'

You don’t have to handle any argument to the built-in exit

5.Simple shell 1.0

Implement the env built-in, that prints the current environment.
6.Simple shell 0.1.1

Write your own getline function

Use a buffer to read many chars at once and call the least possible the read system call

You will need to use static variables

You are not allowed to use getline

Simple shell 0.2.1
You are not allowed to use strtok
Simple shell 0.4.1
handle arguments for the built-in exit

Usage: exit status, where status is an integer used to exit the shell

setenv, unsetenv
setenv

Initialize a new environment variable, or modify an existing one

Command syntax: setenv VARIABLE VALUE

Should print something on stderr on failure.

unsetenv

Remove an environment variable.

Command syntax: unsetenv VARIABLE

Should print something on stderr on failure

cd
Implement the builtin command cd:

Changes the current directory of the process.

Command syntax: cd [DIRECTORY]

If no argument is given to cd the command must be interpreted like cd $HOME

You have to handle the command cd -

You have to update the environment variable PWD when you change directory.

man chdir, man getcwd

;
Handle the commands separator ;
&& and ||
Handle the && and || shell logical operators.
alias
Implement the alias builtin command
Variables
Handle variables replacement - Handle the $? variable - Handle the $$ variable.
Comments
Handle comments (#)
File as input
Your shell can take a file as a command line argument.
