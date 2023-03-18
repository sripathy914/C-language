#include<stdio.h>
int main()
{
    int a,b,c,s=0;
    scanf("%d %d %d",&a,&b,&c);
    int d[12]={31,28,31,30,31,30,31,31,30,31,30,31};
    if((c%400==0)||((c%4==0)&&(c%100==0)))
    d[1]=29;
    for(int i=0;i<b-1;i++)
        s=s+d[i];
    s=s+(a+c+(c/4)-2);
    s=s%7;
    switch(s)
    {
        case 0:
        printf("Sunday");
        break;
        case 1:
        printf("Monday");
        break;
        case 2:
        printf("Tuesday");
        break;
        case 3:
        printf("Wednesday");
        break;
        case 4:
        printf("Thursday");
        break;
        case 5:
        printf("Friday");
        break;
        case 6:
        printf("Saturday");
        break;
        
    }
    
}
