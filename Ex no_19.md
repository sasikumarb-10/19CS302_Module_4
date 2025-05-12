# EX 19 C program to perform basic left and right shift operations on a given integer and display the result.
## DATE:
## AIM:
To write a C program to perform basic left and right shift operations on a given integer and display the result.

## Algorithm
1.Start
2.Declare variables: num, leftShift, rightShift
3.Prompt and read an integer from the user
4.Perform left shift: leftShift = num << 1
5.Perform right shift: rightShift = num >> 1
6.Display the original, left-shifted, and right-shifted values
7.End.

## Program:
```
/*
C program to perform basic left and right shift operations on a given integer and display the result.
Developed by: Sasi Kumar B
RegisterNumber: 212223060252
*/

#include <stdio.h>

int main() {
    int num, leftShift, rightShift;

    printf("Enter an integer: ");
    scanf("%d", &num);

    leftShift = num << 1;
    rightShift = num >> 1;

    printf("Original number: %d\n", num);
    printf("After left shift (num << 1): %d\n", leftShift);
    printf("After right shift (num >> 1): %d\n", rightShift);

    return 0;
}

```

## Output:

![image](https://github.com/user-attachments/assets/2277e61f-ff8d-4214-beb8-8f49d3540a00)


## Result:
Thus the program was executed and the output was verified successfully.
