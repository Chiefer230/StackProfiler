# StackProfiler


A stack profiler in C is a tool used for profiling and analyzing the usage of the stack memory in a C program. It provides insights into the allocation and deallocation of stack frames during the execution of the program.

The stack in C is a region of memory used for local variables, function calls, and other temporary data. As the program executes, the stack grows and shrinks as functions are called and returned. The stack profiler helps identify the stack usage patterns and potential issues such as stack overflow.

A stack profiler typically works by instrumenting the code to track the stack usage. It collects information about the size of stack frames, the number of function calls, and the maximum stack depth reached during program execution. This information can be used to identify hotspots in the code where excessive stack usage occurs.

By analyzing the collected data, a stack profiler can provide valuable insights, such as the maximum stack usage at any given point, the average stack usage, and the distribution of stack sizes across different functions. This information can be useful for optimizing the memory usage and ensuring that the program does not run into stack overflow issues.

Stack profilers can be integrated into the development environment or used as standalone tools. They often provide visual representations, such as graphs or reports, to make it easier to interpret the stack usage data.

In summary, a stack profiler in C is a tool that helps developers understand and optimize the stack usage of their programs. It provides information about stack frame sizes, function call patterns, and overall stack usage, enabling developers to identify and resolve stack-related issues.


# Testing

This program can run on any C program and requires a Linix enviroment inorder to operate. There are two test programs provided that can be used to test.

The Basic Compilation should be done in the Bash Command Line inorder to work.

gcc -c inst.c
gcc -finstrument-functions testfork.c inst.o -o testfork-inst

(Post Issues if found)



# Motivation

The motivation for this project is to understand how a Program works under the Hood. I am very interested in Low level programming and Computer Architecture which is a main reason why i did this project. This project also serves as a smaller subset project for an upcoming a bigger project in observing/countering Buffer Overflows within a program.

  
