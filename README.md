#include<stdio.h>
#include<conio.h>
int main()
{
   int n,sum=0;
   printf("enter a positive integer"):
   scanf("%d",&n);
   while(n>0)
   {
     sum=sum+n%10;
     n=n/10;
   }
   printf("sum of individual digitals of a positive integer is %d",sum);
 }
 
