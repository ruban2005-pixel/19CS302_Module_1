# EX 5C Write a C program to read a year and check whether the year is leap year or not using  if else
## DATE:
## AIM:
To write a program to read a year and check whether the year is leap year or not using  if else.

## Algorithm
1.Start.
2.Read the year value.
3.Check if the year is divisible by 4 (year % 4 == 0).
4.If true, display "Leap Year".
5.Otherwise, display "Not a Leap Year".
6.Stop.
## Program:
```
#include <stdio.h>
int main()
{
    int year;
    scanf("%d", &year);
     if(year%4 == 0)
        printf("Leap Year");
 else
  printf("Not a Leap Year");
          return 0;
}
```

## Output:
<img width="825" height="348" alt="Screenshot 2026-06-08 134511" src="https://github.com/user-attachments/assets/b62a669b-88dd-411b-a8da-6ac75fb77263" />


## Result:
Thus the program was executed and the output was verified successfully.
