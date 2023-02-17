# FIBONACCI.C
C PROGRAME
#include<stdio.h>
int main()
{
	int a=0,b=1,c,n,i;
	printf("enter the number: ");
	scanf("%d",&n);
	printf("\n%d \n%d",a,b);
	for (i=3;i<=n;i++)
	{
		c=a+b;
		printf("\n%d",c);
		a=b;
		b=c;
		
	}
	return 0;
}
