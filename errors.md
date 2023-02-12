# c
ERRORS IN C:
There are many ways a C program can finish in error, including but not limited to:
-File I/O errors: When a file cannot be opened or read due to incorrect path, insufficient permissions, or other reasons.
-Resource allocation errors: When memory or other resources cannot be allocated due to insufficient memory, disk space, or other reasons.
-Division by zero: When a division by zero occurs, usually resulting in an exception or signal.
-Invalid function arguments: When a function is called with invalid or incorrect arguments, resulting in undefined behavior.
-Illegal memory access: When a program tries to access memory that it is not allowed to access, such as trying to read or write to a null pointer or memory outside of the program's memory space.
-Syntax errors: When a program has syntax errors, preventing it from compiling or executing correctly.
-Type mismatches: When data of different types is used in a way that is not compatible, causing type mismatches and undefined behavior.
-Infinite loops: When a program enters an infinite loop, consuming all available resources and causing the program to hang.
-Deadlocks: When two or more processes are waiting for each other to finish, causing the program to hang.

SOME MEMORY ERRORS
--> "Segfault": A "segmentation fault" (often called a segfault) is a specific kind of error caused by accessing memory that 'does not belong to you'. This can happen for many reasons, the most common is when a program tries to read or write an illegal memory location.
--> "Bus error": A "bus error" is another specific kind of error caused by an attempt to access memory that is misaligned, i.e. the memory address being accessed is not properly aligned with the type of data being read.
--> "Double free": "Double free" is an error that occurs when you free the same memory block more than once. This can lead to corruption of the heap, which can result in crashes or other unpredictable behavior.
--> Incorrect usage of memory allocation and deallocation functions, incorrect use of pointers, buffer overflows, incorrect usage of data structures, and more.
