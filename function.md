#include <stdio.h>

// Write the function declaration here
int add(int x , int y);

int main() {
   int result;
   result=add(5,3);
   printf("%d",result);
   return 0;
 }

// Write the function definition here
int add(int x, int y){
     return x+y;
}
