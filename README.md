# Incorrect Use of free() in C
This repository demonstrates a common error in C programming: attempting to free memory allocated on the stack using the `free()` function.  The `free()` function is intended for dynamically allocated memory (using `malloc()`, `calloc()`, etc.). Using it on stack-allocated variables leads to undefined behavior.

The `bug.c` file contains the erroneous code, while `bugSolution.c` shows a corrected version.

**Learn More:**
* Understanding stack vs. heap memory allocation in C
* Proper use of `malloc()`, `calloc()`, `free()`