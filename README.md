#include<stdio.h>
void main()
{
int n,r=0,r1,o;
printf("enter the n value:\n");
scanf("%d",&n);
o=n;
while(n!=0)
{
    r1=n%10;
    r=r*10+r1;
    n=n/10;
}
if(o==r)
{
    printf("%d is a palindrome",o);
    
}
else
{
 printf("%d is not a palindrome",o);   
}}
