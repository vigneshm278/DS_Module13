# Ex5 Stack Operations

## AIM:
To write a C function to perform push and pop operation of the stack in the infix to postfix conversion.

## Algorithm
1. Start the program.
2. Initialize top as -1 and declare stack as a character array.
3. To push, increment top and assign the character to stack[top].
4. To pop, check if top is -1 and return -1 if true.
5. If not, return stack[top] and decrement top.
6. End the program.

## Program:
```
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: Vignesh M
RegisterNumber:  212223240176
*/
char stack[100]; 
int top = -1; 
void push(char x) 
{ 
    stack[++top] = x; 
} 
char pop() 
{ 
    if(top == -1) 
        return -1; 
    else 
        return stack[top--]; 
} 
```

## Output:

![image](https://github.com/user-attachments/assets/4aceaa4e-89d1-4277-94d4-c5e55bca862f)


## Result:
Thus the C program to perform push and pop operation of the stack in the infix to postfix conversion is implemented successfully.
