# Ex2 Conversion of the infix expression into postfix expression
## DATE:13.5.25
## AIM:
To write a C program to convert the infix expression into postfix form using stack by following the operator precedence and associative rule.

## Algorithm
1. Start the program.
2. Include the required libraries.
3. Define functions for push and pop operations to handle the stack and define a function to return the priority of the operators.
4. Construct the function to convert an infix expression into postfix following the logic.
5. End the program.   


## Program:
```
/*
Program to convert the infix expression into postfix expression
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


![Screenshot 2025-05-13 173725](https://github.com/user-attachments/assets/7f793e4f-369f-4966-b550-e243f8601b6b)

## Result:
Thus, the C program to convert the infix expression into postfix form using stack by following the operator precedence and associative rule is implemented successfully.
