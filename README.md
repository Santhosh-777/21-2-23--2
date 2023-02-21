#include<stdio.h>
main()
{
    int n,r,s=0,temp;
    scanf("%d",&n);
    temp=n;
    while(n>0)
    {
        r=n%10;
        s=s+r*r*r;
        n=n/10;
    }
    if(s==temp)
    printf("arm strong");
    else
    printf("not arm strong");
}
