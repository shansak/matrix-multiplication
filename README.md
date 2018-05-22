# matrix-multiplication
#include<stdio.h>
#include<conio.h>
int main()
{
  int a[3][3],b[3][3],c[3][3],sum,i,j,k;
  printf("enter the elements of first matrix");
  for(i=0;i<=2;i++)
    for(j=0;j<=2;j++)
     scanf("%d",&a[i][j]);
     
  printf("enter the elements of second matrix");
  for(i=0;i<=2;i++)
    for(j=0;j<=2;j++)
     scanf("%d",&b[i][j])
     
  for(i=0;i<=2;i++)
   for(j=0;j<=2;j++)
   {
      sum=0;
      sum=sum+a[i][k]*b[k][j];
      c[i][j]=sum;
    }
    for(i=0;i<=2;i++)
     for(j=0;j<=2;j++)
       {
         printf("%d",c[i][j]);
         }
      
      }
