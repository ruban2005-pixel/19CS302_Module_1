# EX 4 C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).
## DATE:
## AIM:
To write a C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).

## Algorithm
1. Start. 
2. Declare a variable value of type char. 
3. Prompt the user to enter a value. 
4. Read the value using scanf. 
5. Check eligible for marriage. 
6. If age >= 21, print "Eligible". 
7. If false, print " Not Eligible". 
8. End. 

## Program:
```
#include<stdio.h> 
int main(){ 
int p1; 
scanf("%d", &p1); 
if(p1>=21) 
{ 
printf("Eligible"); 
}
else
{ 
printf("Not Eligible"); 
} 
return 0; 
} 
```

## Output:
<img width="1132" height="203" alt="image" src="https://github.com/user-attachments/assets/e8b30fa3-0214-4cea-b42d-3521dc9f7422" />



## Result:
Thus the program was executed and the output was verified successfully.
