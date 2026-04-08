#include <stdio.h>

int main() {
    int a, b;
     int oneful;
    scanf("%d %d", &a, &b);
    // Your code goes here (if needed)
    oneful=a+b+(a*b);
    if (oneful == 111){
        printf("YES");
    }
    else{
        printf("NO");
    }
    return 0 ;
}
