# C++ Null Pointer Dereference Bug

This repository demonstrates a common C++ error: dereferencing a null pointer.  The `bug.cpp` file contains the erroneous code, while `bugSolution.cpp` provides a corrected version.

The bug arises from attempting to access memory through a pointer that has not been assigned a valid memory address. This often results in a segmentation fault, causing the program to crash.

The solution involves explicitly checking if the pointer is null before attempting to dereference it.