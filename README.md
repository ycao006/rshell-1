# rshell
UCR Spring 2015

This is Jerome Barbero's version of rshell for Mike Izbicki's UCR Spring 2015 CS100 class.
It is a recreation of linux's bash terminal, where you should be able to read, write and execute files from and all that good computer science stuff.

## hw0 bugs:

1. Could not get || and && to work.

2. Too many spaces before executable cause segfaults.

3. Running too many programs at the same time causes slowdown.

4. If '#' is inside a word it will not count the comment.

5. If exit is not first parameter it will not exit program.
