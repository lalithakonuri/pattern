# pattern
#include<stdio.h>
void main()
{
    int rows;
    printf("Enter rows value:");
    scanf("%d",&rows);
    for (int i = 0; i < rows; i++) 
    { 
          for (int j = 0; j <= i; j++) 
          { 
                printf("* "); 
          } 
        printf("\n"); 
    }
}
    
