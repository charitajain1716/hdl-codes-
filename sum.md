#include <stdio.h>

int main() {
    int a, b;
    // Take inputs and complete the code
    int sum;
    scanf("%d",&a);
    scanf("%d",&b);
    sum=a+b;
    
   if (sum % 2 == 0){
        printf("YES");
    }
    else{
        printf("NO");
    }
    return 0;
}
