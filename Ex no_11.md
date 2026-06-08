# EX 11 C Program to convert a given decimal value to binary using function without arguments with return type.

## DATE:
08.06.2026

## AIM:
To write a C Program to convert a given decimal value to binary using function without arguments with return type.

## Algorithm

1. Start the program.
2. Declare a function to convert decimal to binary.
3. Get the decimal number from the user.
4. Convert the decimal number into binary form.
5. Return the binary value from the function.
6. Display the binary value.
7. Stop the program.

## Program:

```c
#include <stdio.h>

int n;

long int binary()
{
    int rem;
    long int bin = 0, place = 1;

    while(n > 0)
    {
        rem = n % 2;
        bin = bin + (rem * place);
        place = place * 10;
        n = n / 2;
    }

    return bin;
}

int main()
{
    long int result;

    scanf("%d", &n);

    result = binary();

    printf("%ld", result);

    return 0;
}
```

## Output:

```text
10

1010
```

## Result:
Thus the program was executed and the output was verified successfully.
