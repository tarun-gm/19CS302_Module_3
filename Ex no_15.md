# EX 15 C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.

## DATE:
08.06.2026

## AIM:
To write a C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.

## Algorithm

1. Start the program.
2. Declare array and variables.
3. Get the size of the array.
4. Read the array elements from the user.
5. Traverse the array using loop.
6. Check whether each element is even.
7. If even, print 'E'.
8. Otherwise, print the element.
9. Stop the program.

## Program:

```c
#include <stdio.h>

int main()
{
    int a[10], n, i;

    scanf("%d", &n);

    for(i = 0; i < n; i++)
    {
        scanf("%d", &a[i]);
    }

    for(i = 0; i < n; i++)
    {
        if(a[i] % 2 == 0)
        {
            printf("E ");
        }
        else
        {
            printf("%d ", a[i]);
        }
    }

    return 0;
}
```

## Output:

```text
5
1 2 3 4 5

1 E 3 E 5
```

## Result:
Thus the program was executed and the output was verified successfully.
