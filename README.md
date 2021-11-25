//number-pattern01-Aswathi-K

#include <stdio.h>
void main()
{
int i,j,k;
for(i=2;i<=8;i++)
{
k=i+1;
for(j=1;j<=i;j++)
{
printf("%d",k%2);
k++;
}
printf("\n");
}
}
