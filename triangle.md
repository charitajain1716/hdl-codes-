#include <stdio.h>

int main() {
    // Your code goes here
     int a,b,c;
     scanf("%d",&a);
     scanf("%d",&b);
     scanf("%d",&c);
     
   if ((a==b) && (b==c)){
        printf("Equilateral");
    }
    else if((a!=b && b!=c) && c!=a){
        printf("Scalene");
    }
    else{
        printf("Isosceles");
    }
    return 0;
}
