# c
lseek is a system call in C that changes the file offset for a file descriptor. 
The file offset is a value that indicates the current position in a file, and it determines where the next read or write operation will occur. 
The lseek function allows you to change the file offset to a specific location in a file. It takes three arguments: 
a file descriptor, an offset value, and a flag that determines the starting position for the offset 
(e.g. the beginning of the file, the current position, or the end of the file). 
The return value of lseek is the new file offset, or -1 if an error occurs.
