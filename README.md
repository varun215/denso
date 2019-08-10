#include <stdio.h>

int main()
{
	int n,n1,i=1,j;
	scanf("%d%d",&n,&n1);
	while(n>=1)
	{
	    
	    j=n-n*(n1*0.01);
	    n=j;
	    i++;
	}
	printf("%d",i);
	return 0;
}
