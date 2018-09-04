# swap_pgm
Swapping of two programs using Arithmatic operators


#include <stdio.h>
 
int main()
{
   int x, y, temp;
 
   printf("Enter the value of x and y\n");
   scanf("%d%d", &x, &y);
 
   printf("Before Swapping\nx = %d\ny = %d\n",x,y);
 
   x    = x+y;
   x    = x-y;
   y    = x-y;
 
   printf("After Swapping\nx = %d\ny = %d\n",x,y);
 
   return 0;
}
