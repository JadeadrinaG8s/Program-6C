# Program-6C
C module 6
EX NO-6)C) a book structure read and print the details of book.
DATE:20/10/25
NAME:JADE ADRINA J
REF NO:25017000
AIM:TO Create a book structure read and print the details of book.
ALGORITHM:
1)Write a book structure .2)call the structure.3)take input from the user and print the values using printf() function.
PROGRAM:
```
#include <stdio.h>

struct details
{
    char name[50];
    float value1;
    int value2;
};

int main()
{
    struct details d;

    // Input
    scanf("%s %f %d", d.name, &d.value1, &d.value2);

    // Output
    printf("And this is what you entered\n");
    printf("%s %.2f %d", d.name, d.value1, d.value2);

    return 0;
}
```
OUTPUT:
<img width="899" height="220" alt="Screenshot 2025-10-20 091831" src="https://github.com/user-attachments/assets/795b55cd-6354-4a5d-9bc5-2eea8bcf083a" />
RESULT:
Thus,a a book structure read and print the details of book has been created successfully.


