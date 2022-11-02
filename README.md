# odev1-soru2

#include <stdio.h>

int main(int argc, const char * argv[]) {
    // insert code here...
    
    int sum1 = 0;
    int sum2 = 0;
    
    for(int i = 1; i<=100; i++){
        sum1 += i*i;
        sum2 += i;
    }
    int result = sum2*sum2 - sum1;
    printf("sonuc = %d ",result);
    return 0;
