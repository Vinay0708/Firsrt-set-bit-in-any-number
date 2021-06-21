# Firsrt-set-bit-in-any-number
#include<stdio.h>
#include<math.h>
int main()
{   
    int n,x,y;
    printf("Please provide a number:\n");
    scanf("%d",&n);
    x=n&(n-1);
    y=log(n^x)/log(2);
    printf("The position of first set bits are:%d",y+1);
    return 0;
}
