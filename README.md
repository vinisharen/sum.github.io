#include<stdio.h>
void main()
{
	int n,i,sum=0;
	printf("enter the number\n");
	scanf("%d",&n);
	for(i=0;i<n;i++)
	{
          if(i%3==0)
          {
          sum=i+sum;
          }
            
          }
           printf("%d",sum);
}
