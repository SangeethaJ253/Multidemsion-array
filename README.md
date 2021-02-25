# Multidemsion-array
using 3d array
#include <stdio.h>

int main()
{
  int test1[3][3]i,j;
  
        printf("3d array elments\n");  
  
       printf("Input elements in the matrix :\n");
  for(i=0;i<3;i++)
  {
      for(j=0;j<3;j++)
      {
	      printf("element [%d],[%d] : ",i,j);
	      scanf("%d",&test1[i][j]);
      }
  }  
 
 printf("\nThe matrix is : \n");
  for(i=0;i<3;i++)
  {
      printf("\n");
      for(j=0;j<3;j++)
           printf("%d\t",test1[i][j]);
  }
 
}

                 
