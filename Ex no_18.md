# EX 18 C program to find frequency of a character in the given input.
## DATE: 21-05-2025
## AIM:
To write a C program to find frequency of a character in the given input.

## Algorithm
1.Start the program. 
2.Read the input string from the user.
3.Read the character whose frequency needs to be found. 
4.Traverse the string and count how many times the character appears.
5.Print the frequency and end the program. 

## Program:
```
/*
C program to find frequency of a character in the given input.
Developed by: AASHIKA PARVEEN M R
RegisterNumber: 212223060002  
*/

#include <stdio.h>

int main() {
    char str[1000], ch;
    int i = 0, count = 0;

    printf("Enter a string: ");
    fgets(str, sizeof(str), stdin);

    printf("Enter the character to find frequency: ");
    scanf("%c", &ch);

    while(str[i] != '\0') {
        if(str[i] == ch)
            count++;
        i++;
    }

    printf("Frequency of '%c' = %d\n", ch, count);

    return 0;
}
```

## Output:
![444994050-adfa6412-c86e-46f1-a7b8-955354e616ea](https://github.com/user-attachments/assets/59c23bfd-4d82-404f-bb1c-16e38c765d2c)


## Result:
Thus the program was executed and the output was verified successfully.
