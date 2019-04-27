/*
TO FIND LCM & HCF OF 2 NUMBERS
*/
#include <stdio.h>
int find(int a,int b)
{
    return a==0?b:find(b%a,a);
}
int main()
{
int a,b;
scanf("%d %d",&a,&b);
int hcf=find(a,b);
int lcm=(a*b)/hcf;
printf("%d %d",lcm,hcf);
    return 0;
}
