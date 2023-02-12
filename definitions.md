# c

heap: In the context of computer science and programming, the heap is a region of memory used for dynamic memory allocation. 
The heap is different from the stack, which is used for storing function call frames and temporary data. 
In C, the heap is used to allocate memory dynamically during program execution using functions such as malloc() and calloc(). 
The memory in the heap can be freed when it's no longer needed, making it ideal for managing complex data structures and large objects. 
However, dynamically allocating memory from the heap requires manual management and can result in memory leaks if not done correctly.

size_t: is an unsigned integer data type that is used to represent the size of objects in bytes. 
It is defined in the standard library header stddef.h and is typically used for arrays and memory allocation functions such as malloc(), realloc(), and sizeof(). 
The exact size of size_t is implementation-defined and may depend on the underlying hardware architecture.

memory leaks: In C programming, a memory leak occurs when a program dynamically allocates memory using malloc, calloc, realloc, etc., but fails to release it properly. 
The memory is still allocated and can no longer be used by the program, but is not released back to the operating system, 
leading to a slow and steady depletion of available memory. 
Over time, this can cause the program to crash or become unresponsive. 
To avoid memory leaks, it's important to free dynamically allocated memory when it's no longer needed, using the free function.

FILE DESCRIPTOR
A file descriptor is an integer value that is used to identify an open file in a computer's operating system. 
It provides a unique reference to a file that is used to perform operations such as reading, writing, or seeking within the file. 
A file descriptor is created when a file is opened and is returned by the operating system as the result of a successful open() system call. 
The file descriptor is used to reference the file in subsequent I/O operations until it is closed with a close() system call.

Examples of file descriptors in C language:
Standard Input (STDIN): represented by file descriptor 0.
Standard Output (STDOUT): represented by file descriptor 1.
Standard Error (STDERR): represented by file descriptor 2.
An open file in a program: represented by a non-negative integer, which can be obtained using the open system call.
Pipes: A pipe is a communication channel between two processes and has a file descriptor associated with it. A pipe has a read end and a write end, represented by two separate file descriptors.

STATIC VARIABLE
In C, a static variable is a variable that retains its value between function calls. 
When a variable is declared as static, it is only initialized once, the first time the function is called. 
On subsequent calls to the same function, the value of the static variable is preserved, allowing the function to remember its state across multiple invocations. 
This makes static variables useful for maintaining state across function calls, without the need to pass state as arguments to the function or use global variables.

GLOBAL VARIABLE

