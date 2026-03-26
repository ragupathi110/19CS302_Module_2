# EX 10 C program to find the factorial of a given number using a function with arguments and return type.
## DATE:
## AIM:
To write a C program to find the factorial of a given number using a function with arguments and return type.

## Algorithm
1. Start  
2. Declare function `factorial(int n)`  
3. Initialize `fact = 1`  
4. Loop from `i = 1` to `n`  
5. Multiply `fact = fact * i`  
6. Return `fact`  
7. In `main()`, declare `num`  
8. Read `num` from user  
9. Call `factorial(num)` and store in `result`  
10. Print `result`  
11. End
    
## Program:
```
/*
Program to find the factorial of a given number using a function with arguments and return type.
Developed by: Ragupathi Raj M
RegisterNumber: 212222060185
*/
#include <stdio.h>
int factorial(int n) {
    int fact = 1;
    for (int i = 1; i <= n; ++i) {
        fact *= i;
    }
    return fact;
}
int main() {
    int num;
    printf("Enter a number: ");
    scanf("%d", &num);
    int result = factorial(num);
    printf("Factorial of %d is %d\n", num, result);
    return 0;
}
```

## Output:

![image](https://github.com/user-attachments/assets/8d6a4b91-ce07-4fa4-8dc2-6c16bd26758e)

## Result:
Thus the program was executed and the output was verified successfully.
