/* This lab is designed to simulate a race using forked processes */
/* Lab 10 - Jake Breitfeller */

I compiled nephew.c using the following

gcc nephew.c -o nephew

popeye.c uses ./nephew in exec() to run nephew.c so it must be compiled this way for the program to work
