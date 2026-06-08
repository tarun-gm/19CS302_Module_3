# EX 13 To write a C program to read the elements and print only the odd elements in the 2D array.

## DATE:
08.06.2026

## AIM:
To write a C program to read the elements and print only the odd elements in the 2D array.

## Algorithm

1. Start the program.
2. Declare a 2D array and variables.
3. Get the number of rows and columns.
4. Read the array elements from the user.
5. Traverse the array using nested loops.
6. Check whether each element is odd.
7. Print the odd elements.
8. Stop the program.

## Program:

```c
#include <stdio.h>

int main()
{
    int a[10][10], i, j, r, c;

    scanf("%d %d", &r, &c);

    for(i = 0; i < r; i++)
    {
        for(j = 0; j < c; j++)
        {
            scanf("%d", &a[i][j]);
        }
    }

    for(i = 0; i < r; i++)
    {
        for(j = 0; j < c; j++)
        {
            if(a[i][j] % 2 != 0)
            {
                printf("%d ", a[i][j]);
            }
        }
    }

    return 0;
}
```

## Output:

```text
2 3
1 2 3
4 5 6

1 3 5
```

## Result:
Thus the program was executed and the output was verified successfully.
