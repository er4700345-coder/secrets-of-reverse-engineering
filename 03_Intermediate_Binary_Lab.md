# Intermediate Binary Lab

This lab builds on the first binary lab by introducing **conditional logic and loops** in the binary for analysis.

## Program: loop_calc.c

```c
#include <stdio.h>

int main() {
    int total = 0;
    for(int i = 1; i <= 5; i++) {
        total += i;
    }
    printf("Total sum: %d\n", total);
    return 0;
}
