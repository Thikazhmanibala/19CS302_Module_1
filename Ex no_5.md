# EX 5 C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.
## AIM:
To write a C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.

## Algorithm
1. Read marks of 7 subjects.
2. Calculate the total by summing all marks.
3. Find the average by dividing total by 7.
4. Assign percentage as equal to average (since each subject is out of 100).
5. Display total, average, and percentage.
 

## Program:
```
/*
Program to calculate the total marks, average, and percentage of marks obtained in seven subjects.
Developed by: Thikazhmanibala.K
RegisterNumber:  212222060277
#include <stdio.h>
int main()
{
    int a,b,c,d,e,f,g;
    scanf("%d%d%d%d%d%d%d",&a,&b,&c,&d,&e,&f,&g);
    
    float total=a+b+c+d+e+f+g;
    float average=total/7;
    float percentage=total/7;
    
    printf("Total marks = %.2f\nAverage marks = %.2f\nPercentage = %.2f",total,average,percentage);
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/dbbd83c4-0f6c-4b63-a833-47513521f6ac)


## Result:
Thus the program was executed and the output was verified successfully.
