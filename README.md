
#include <stdio.h>
float div(int a,int b)
{
    return ((float)a/(float)b);
}
int main()
{
    int c,d;
    scanf("%d%d",&c,&d);
    float res=div(c,d);
    printf("%1f",res);
}
