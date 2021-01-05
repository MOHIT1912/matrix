
#include<stdio.h>
#include<conio.h>
int main()
{
	int a[5][5],b[5][5],c[5][5],i,j,k,c1,r1,r2,c2;
	printf("enter the value of first row and column ");
	scanf("%d%d",&r1,&c1);
	printf("enter the value of second row and column ");
	scanf("%d%d",&r2,&c2);
	printf("enter emlement of first ");
    for(i=0;i<r1;i++)
    {
    	for(j=0;j<c1;j++)
    	{
    		scanf("%d",&a[i][j]);
    		
		}
    }
	printf("enter the element of second ");
    for(i=0;i<r2;i++)
    {
    	for(j=0;j<c2;j++)
    	{
    		scanf("%d",&b[i][j]);
		}
	}
	    for(i=0;i<r1;i++)
    {
    	for(j=0;j<c1;j++)
    	{
    		printf("%d\t",a[i][j]);
    		
		}printf("\n\n");
    }
    
        for(i=0;i<r2;i++)
    {
    	for(j=0;j<c2;j++)
    	{
    		printf("%d\t",b[i][j]);
		}printf("\n\n");
	}
	getch();
	return(0);
}
