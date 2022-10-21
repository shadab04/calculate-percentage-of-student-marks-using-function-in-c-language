# calculate-percentage-of-student-marks-using-function-in-c-language
#include<stdio.h>
int percentage(int m ,int e,int p);
int main()
{
    int m=90,e=95,p=100;
    printf("percentage is:\n%d",percentage(e,m,p));
}
int percentage(int m ,int e,int p)
{
    return ((e+m+p)/3);
}
