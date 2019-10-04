# Operating-systems-assignments

Your job is to implement a very basic shell. It should accept input from the command line,
parse it, and run the executable specified. More specfic steps are provided in the shell.c file.

This will also provide practice with reading manual pages (or man pages for short). These are
extremely useful for understanding these system calls at a deeper level. For instance,
what arguments do the functions expect? What format should the arguments be? What does this
function return?

hello.c - Simple C program that contains the source code for the hello executable.
hello - executable that you should be able to run in your shell.
Makefile - Makefile for the shell and hello executable. Run `make shell` and `make hello` respectively.
ref_shell - executable of the solution, for your reference. You can run `./ref_shell` in the terminal
            to see what your shell should be doing.
shell.c - where you implement your shell!
