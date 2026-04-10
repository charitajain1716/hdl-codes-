#include <stdio.h>

int main() {
	// your code goes here
	int i=1;
	int n;
	int sum=0;
	scanf("%d",&n);
	while(i<=n){
	    if(i%2==0){
	        sum += i;
	        i++;
	    }
	   i++;
	}
   printf("%d",sum);
   return 0 ;
}

