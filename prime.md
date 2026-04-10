int main() {
    int num,i=2,isprime=1;
    scanf("%d", &num);
    // Complete the code
    if (num<2){
        isprime=0;
    }
    else{
        while(i*i<=num){
            if (num%i==0){
                isprime=0;
                break;
            }
            i++;
        }
    }
    if (isprime)
        printf("YES");
    else
        printf("No");
    return 0;
}
