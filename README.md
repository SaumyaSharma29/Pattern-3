# Pattern-3

#include<stdio.h>
int main()
{
int n,i,j;
for(i=0;i<n;i++)
{
for(j=i;j>0;j--)
{
printf(" ");
}
for(j=n-i;j>0;j--)
{
printf("*");
}
}
}
