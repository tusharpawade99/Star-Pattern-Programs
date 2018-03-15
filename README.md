# Star-Pattern-Programs

1.Consider the following triangle pattern

    *
   ***
  *****
 *******
*********

code below:-
#include <stdio.h>
 
int main()
{
   int row, c, n, temp;
 
   printf("Enter the number of rows in pyramid of stars you wish to see ");
   scanf("%d",&n);
 
   temp = n;
 
   for ( row = 1 ; row <= n ; row++ )
   {
      for ( c = 1 ; c < temp ; c++ )
         printf(" "); // space
 
      temp--;
 
      for ( c = 1 ; c <= 2*row - 1 ; c++ )
         printf("*");
 
      printf("\n");
   }
 
   return 0;
}

2.Consider the following triangle pattern

*
**
***
****
*****

code:
#include <stdio.h>
 
int main()
{
    int n, c, k;
 
    printf("Enter number of rows\n");
    scanf("%d",&n);
 
    for ( c = 1 ; c <= n ; c++ )
    {
        for( k = 1 ; k <= c ; k++ )
            printf("*");
 
        printf("\n");
    }
 
    return 0;
}
