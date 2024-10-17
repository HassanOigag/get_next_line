# Get Next Line - 42 Project

**Get Next Line** (GNL) is a project aimed at reading a line from a file descriptor efficiently. This function allows reading from a file, standard input, or even a network socket line-by-line, which is an essential part of many applications.

## About

The **Get Next Line** project implements a function that reads a single line from a file descriptor (such as a file or input stream) each time it is called. This is crucial for handling dynamic input or reading files without knowing their size in advance. 

The function prototype is:

```c
int get_next_line(int fd);
