#include<stdio.h>
#include<math.h>
int main()
{
float x,p;
scanf("%f,%f",&x,&p);
float n,r;
int res=0;
while(x!=0)
{
r=p/100*x;
n=floor(x-r);
res=res+x;
x=n;
}
printf("%d\n",res);
}

