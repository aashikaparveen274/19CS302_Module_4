# EX 19 C program to perform basic left and right shift operations on a given integer and display the result.
## DATE: 21-05-2025
## AIM:
To write a C program to perform basic left and right shift operations on a given integer and display the result.

## Algorithm
1.Start the program. 
2.Read an integer and the number of positions to shift.
3.Perform left shift (<<) on the integer by the given positions. 
4.Perform right shift (>>) on the integer by the given positions.
5.Display the results and end the program.    

## Program:
```
/*
C program to perform basic left and right shift operations on a given integer and display the result.
Developed by: AASHIKA PARVEEN M R
RegisterNumber: 212223060002
*/

#include <stdio.h>

int main() {
    int num, shift;
    int leftShift, rightShift;

    printf("Enter an integer: ");
    scanf("%d", &num);

    printf("Enter number of positions to shift: ");
    scanf("%d", &shift);

    leftShift = num << shift;
    rightShift = num >> shift;

    printf("Result after left shift by %d positions: %d\n", shift, leftShift);
    printf("Result after right shift by %d positions: %d\n", shift, rightShift);

    return 0;
}
```

## Output:
![444994691-661ee331-3fac-4c14-9922-8003f824b3e2](https://github.com/user-attachments/assets/2f5d786e-1969-4bc6-9f1c-ce99b28377c3)



## Result:
Thus the program was executed and the output was verified successfully.
