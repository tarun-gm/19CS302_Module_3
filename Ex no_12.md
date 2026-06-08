# EX 12 C program to check whether the given number is prime or not using function without return type and with arguments.

## DATE:
08.06.2026

## AIM:
To write a C program to check whether the given number is prime or not using function without return type and with arguments.

## Algorithm

1. Start the program.
2. Declare a function to check prime number.
3. Get the number from the user.
4. Pass the number to the function.
5. Check whether the number is divisible by any number other than 1 and itself.
6. If divisible, display Not Prime.
7. Otherwise, display Prime.
8. Stop the program.

## Program:

```c
#include <stdio.h>

void prime(int n)
{
    int i, flag = 0;

    for(i = 2; i < n; i++)
    {
        if(n % i == 0)
        {
            flag = 1;
            break;
        }
    }

    if(flag == 0)
    {
        printf("Prime");
    }
    else
    {
        printf("Not Prime");
    }
}

int main()
{
    int n;

    scanf("%d", &n);

    prime(n);

    return 0;
}
```

## Output:

```text
7

Prime
```

## Result:
Thus the program was executed and the output was verified successfully.
