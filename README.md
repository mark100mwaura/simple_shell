simple_shell
ALX Simple Shell Group/Team Project by @PeterOpanga and @Mark100Mwaura

simple_shell project repository
This repository contains the files for ALX's simple_shell. It can be compiled using GCC and will execute a simple shell that can be used for some basic tasks and programs most commonly found in the /bin/ folder.

Table of contents
What is shell?

Authorized functions and macros

Usage

Collaborators

What is Shell?
The shell is the layer of programming that understands and executes the commands a user enters. In some systems, the shell is called a command interpreter. A shell usually implies an interface with a command syntax. This project is a simple version of the linux shell

Authorized functions and macros
access (man 2 access)

chdir (man 2 chdir)

close (man 2 close)

closedir (man 3 closedir)

execve (man 2 execve)

exit (man 3 exit)

_exit (man 2 _exit)

fflush (man 3 fflush)

fork (man 2 fork)

free (man 3 free)

getcwd (man 3 getcwd)

getline (man 3 getline)

getpid (man 2 getpid)

isatty (man 3 isatty)

kill (man 2 kill)

malloc (man 3 malloc)

open (man 2 open)

opendir (man 3 opendir)

perror (man 3 perror)

read (man 2 read)

readdir (man 3 readdir)

signal (man 2 signal)

stat (__xstat) (man 2 stat)

lstat (__lxstat) (man 2 lstat)

fstat (__fxstat) (man 2 fstat)

strtok (man 3 strtok)

wait (man 2 wait)

waitpid (man 2 waitpid)

wait3 (man 2 wait3)

wait4 (man 2 wait4)

write (man 2 write)

Usage
Step 1: Clone our repository using this command, (you need to have git installed on your machine first) git clone https://github.com/PeterOpanga/simple_shell

Step 2: Change directory to simple_shell: cd simple_shell

Step 3: Compile the C files in this way: gcc -Wall -Werror -Wextra -pedantic *.c -o hsh

Step 4: Run the shell ./hsh

To exit the shell:
Press on Ctrl + D

Collaborators
Peter Ogallo Mark Kariuki
