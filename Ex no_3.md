# EX 3 C program to find number of years based on principle,rate & simple interest.
## AIM:
To write a C program to find number of years based on principle,rate & simple interest.

## Algorithm
1. Read Amount, Time, and Rate from the user.
2. Use the formula: Principal = Amount / (1 + Rate/100)^Time.
3. Calculate the principal value using the formula.
4. Display the principal amount.
  

## Program:
```
/*
Program to find number of years based on principle,rate & simple interest.
Developed by: Thikazhmanibala.K
RegisterNumber:  212222060277
#include <stdio.h>
#include <math.h>

int main()
{
    float principal_amount, rate_of_interest, time,compound_interest;
    
    scanf("%f", &compound_interest);
    scanf("%f", &time);
    scanf("%f", &rate_of_interest);
    
    principal_amount = compound_interest / (pow((1 + (rate_of_interest / 100)), time));
    
    printf("Principle Amount is = %.2f", principal_amount);
    
    return 0;
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/9970da37-69c1-4a73-b739-87ab076ce2db)


## Result:
Thus the program was executed and the output was verified successfully.
