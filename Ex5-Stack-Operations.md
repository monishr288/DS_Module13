# Ex5 Stack Operations
## DATE:13.5.25
## AIM:
To write a C function to perform push and pop operation of the stack in the infix to postfix conversion.

## Algorithm
1. Start the program.
2. Include the required libraries.
3. Define a function to perform push operation of a stack by incrementing the top pointer.
4. Define a function to perform pull operation of a stack by decrementing the top pointer and returning the element before decrementing.
5. End the program.
  

## Program:
```
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: MONISH R
RegisterNumber:  212223220061
*/
#include<stdio.h>

char stack[100];
int top = -1;

void push(char x)
{
   top++;
   stack[top]=x;
}

char pop()
{
    return stack[top--];
  
}
```

## Output:



![Screenshot 2025-05-13 173725](https://github.com/user-attachments/assets/e82352f7-04bd-49d2-b553-a89cfc267952)


## Result:
Thus the C program to perform push and pop operation of the stack in the infix to postfix conversion is implemented successfully.
