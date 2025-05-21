# EX 20 C program to convert the given string to lowercase without using string functions.
## DATE: 21-05-2025
## AIM:
To write a C program to convert the given string to lowercase without using string functions.

## Algorithm
1.Start the program. 
2.Read the input string from the user.
3.Traverse each character of the string until the null terminator is reached.
4.If the character is uppercase (between 'A' and 'Z'), convert it to lowercase by adding 32.
5.Print the converted string and end the program. 

## Program:
```
/*
C program to convert the given string to lowercase without using string functions.
Developed by: AASHIKA PARVEEN M R
RegisterNumber: 212223060002
*/

#include <stdio.h>

int main() {
    char str[1000];
    int i = 0;

    printf("Enter a string: ");
    fgets(str, sizeof(str), stdin);

    while(str[i] != '\0') {
        if(str[i] >= 'A' && str[i] <= 'Z') {
            str[i] = str[i] + 32;  // Convert uppercase to lowercase
        }
        i++;
    }

    printf("Lowercase string: %s", str);

    return 0;
}
```

## Output:
![444995632-ac948b07-4ed3-483e-abf0-4d7873201327](https://github.com/user-attachments/assets/dff8eac2-ba53-4c41-97fa-eb368d8e59eb)



## Result:
Thus the program was executed and the output was verified successfully.
