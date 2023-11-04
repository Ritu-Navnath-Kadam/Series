# Series
#include<stdio.h>
#include<math.h>

int fact(int);
int fact(int n)
{
if(n==1 || n==1)
return  1;
else
return (n*fact(n-1));

}
void main()
{
int n,sum,r=0,s,x,q=0;
printf("enter a number : ");
scanf("%d",&n);

printf("enter x : ");
scanf("%d",&x);

for(int i=1;i<=n;i++)
{
sum=pow(x,i);
s=fact(i);
printf("%d/%d \t",sum,s);
printf ("\n\n");
{
r=(sum/s);
q=q+r;
}
}
printf("sum of first %d terms = %f",n,(float)q);

}
