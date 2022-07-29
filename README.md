# 1-to-45-Codes-from-List-of-programs
1 to 45 codes from the "List of programs" of CSE 103

1. Write a C program to get an input from keyboard and print it.
Ans :-

2. Write a C program to get two numbers from keyboard and add them.
Ans :-

#include<stdio.h>

int main()

{
    int A,B,sum;
    
    printf("Enter the value of 1st number =");
    scanf("%d",&A);
    printf("Enter the value of 2ed number =");
    scanf("%d",&B);
    
    sum=A+B;
    
    printf("The sum of two number = %d\n", sum);
    return 0;
}

