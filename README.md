# Division by Zero Bug in C

This repository demonstrates a common error in C programming: division by zero.  The code attempts to divide an integer by zero, which is undefined behavior. This can lead to program crashes or unpredictable outputs.

The solution demonstrates how to prevent this by adding a check for the divisor being zero before performing the division.

## How to reproduce

1. Clone this repository.
2. Compile the `bug.c` file using a C compiler (like GCC): `gcc bug.c -o bug`
3. Run the executable: `./bug`

You will likely observe that the program crashes or exhibits unexpected behavior.

## Solution

The `bugSolution.c` file provides a corrected version of the code that handles the potential division by zero error gracefully.