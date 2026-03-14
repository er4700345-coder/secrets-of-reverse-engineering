# First Binary Lab

This lab introduces your first binary for reverse engineering. A simple C program is created to analyze function flow and memory layout.

## Program: simple_calc.c

```c
#include <stdio.h>

int add(int a, int b) {
    return a + b;
}

int main() {
    int x = 5, y = 7;
    int sum = add(x, y);
    printf("Sum: %d\n", sum);
    return 0;
}
