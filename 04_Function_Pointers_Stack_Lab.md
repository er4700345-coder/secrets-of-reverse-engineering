# Function Pointers & Stack Lab

This lab introduces **function pointers and stack behavior** for deeper reverse engineering practice.

## Program: func_ptr_stack.c

```c
#include <stdio.h>

void greet() {
    printf("Hello from greet()!\n");
}

void farewell() {
    printf("Goodbye from farewell()!\n");
}

int main() {
    void (*func_ptr)();

    func_ptr = &greet;
    func_ptr();

    func_ptr = &farewell;
    func_ptr();

    return 0;
}
