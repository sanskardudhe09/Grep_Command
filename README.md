# Grep_Command
This repository contains all the source code files of my DSA Mini Project "Grep" implemented in C language
Implementation of Grep commands[Global Regulation Expression Print]

Aim: To search a file for a particular string.

REFERENCE TO VARIOUS FUNCTIONS

The Program uses token and mystrstr functions to find the pattern and print the lines containing the pattern.

token divides the file content into single lines and searches for the pattern.

Various options implemented are shown in ./grep -h.

-r option which traverses through directories. It is implemented in dir.c. dirent.h is used to do so. mystrstrcase function ignores case to search pattern.
