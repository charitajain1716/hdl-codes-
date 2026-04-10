#include <stdio.h>

int main() {
    int n,sum=0,remainder;
    scanf("%d", &n);
    // Complete the code
    while (n!=0){
        remainder=n%10;
        sum=sum+remainder;
        n/=10;
    }
    printf("%d",sum);
    return 0;
}
