# EX 17 C Program to compare two strings without using strcmp().
## DATE: 21-05-2025
## AIM:
To write a C Program to compare two strings without using strcmp().

## Algorithm
1. Start the program.
2. Read two strings from the user using scanf.
3. Initialize an index i and compare characters at position i of both strings.
4. If characters differ at any position, mark strings as not equal and stop; if both strings end together without mismatch, they are equal. 
5. Print whether the strings are equal or not and end the program.  

## Program:
```
/*
 C Program to compare two strings without using strcmp().
Developed by: AASHIKA PARVEEN M R
RegisterNumber: 212223060002
*/

#include <stdio.h>

int main() {
    char str1[100], str2[100];
    int i = 0, flag = 0;

    printf("Enter first string: ");
    scanf("%99s", str1);  // reads string safely, max 99 chars
    printf("Enter second string: ");
    scanf("%99s", str2);

    while(str1[i] != '\0' && str2[i] != '\0') {
        if(str1[i] != str2[i]) {
            flag = 1;
            break;
        }
        i++;
    }

    if(flag == 0 && str1[i] == '\0' && str2[i] == '\0')
        printf("Strings are equal\n");
    else
        printf("Strings are not equal\n");

    return 0;
}
```

## Output:
![444993541-b388108c-36d0-4949-8105-f211e22e9f14](https://github.com/user-attachments/assets/a194f9b7-d839-4d35-a796-eecf1e73c7ed)



## Result:
Thus the program was executed and the output was verified successfully.
