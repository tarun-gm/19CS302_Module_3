# EX 14 C program to delete first element in an array.

## DATE:
08.06.2026

## AIM:
To write a C program to delete first element in an array.

## Algorithm

1. Start the program.
2. Declare array and variables.
3. Get the size of the array.
4. Read the array elements from the user.
5. Shift all elements one position to the left.
6. Reduce the array size by one.
7. Display the updated array.
8. Stop the program.

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

    for(i = 0; i < n - 1; i++)
    {
        a[i] = a[i + 1];
    }

    n--;

    for(i = 0; i < n; i++)
    {
        printf("%d ", a[i]);
    }

    return 0;
}
```

## Output:

```text
5
10 20 30 40 50

20 30 40 50
```

## Result:
Thus the program was executed and the output was verified successfully.
