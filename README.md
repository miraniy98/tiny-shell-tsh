# tiny-shell-tsh
A tiny shell program with job-control.
## Files:
* tsh.c - Main shell program written in C language
* myspin.c - Spins for number of seconds taken in as argument
* mysplit.c - Forks a child that spins for number of seconds taken in as argument
* myint.c - Spins for number of seconds taken in as argument and then sends SIGINT signal to itself
* mystop.c - Spins for number of seconds taken in as argument and then sends SIGTSTP signal to itself
* tshref.out - Reference shell output in terms of trace files-
* sdriver.pl - trace-driven shell driver written in Perl
* ALL THE TRACE FILES - files to understand working of the shell and verify with tshref.out
* Makefile - Compiles all the above programs

## Features:
* Operate the processes as background or foreground processes
* Convert the background process to foreground process by referencing with job-id OR process-id
* Stop and resume foreground process
* Run other codes and commands via shell
