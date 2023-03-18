/*
A Hailstone series is defined as follows: start with any integer value greater than 0, say x. If x is even, then the next value in the series is x/2; if x is odd, then the next value in the series is 3x + 1. Now apply the same rules to create the next value in the series, and so on.
*/

#include<stdio.h>
int main()
{
    int a,b,c;
    scanf("%d %d",&a,&b);
    for(int i=0;i<b;i++)
    {
        if(i==0)
        {
            c=a;
            printf("%d ",a);
            continue;
        }
        if(c%2==0)
        c/=2;
        else
        c=3*c + 1;
    printf("%d ",c);
}
}
