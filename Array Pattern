#include<stdio.h>
int main()
{
    int n,i,j;
    scanf("%d",&n);
    int m=2*n -1;
    int ar[50][50];
    for(i=0;i<m;i++)
    {
        for(j=i;j<=m-i-1;j++)
            ar[i][j]=n;
        for(j=i+1;j<=m-i-1;j++)
            ar[j][m-i-1]=n;
        for(j=m-i-2;j>=i;j--)
            ar[m-i-1][j]=n;
        for(j=m-i-2;j>i;j--)
            ar[j][i]=n;
        n--    
    }
    for(i=0;i<m;i++)
    {
        for(j=0;j<m;j++)
            printf("%d ",ar[i][j]);
        printf("\n");
    }
}
