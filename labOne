// include stdio.h
#include <stdio.h>

int largestNumber (int a, int b, int c); // function prototype
int smallestNumber (int a, int b, int c); // function prototype

// main function    
int main() {
    int a, b, c; // declare three integers
    printf("Enter three integers seperated by space: "); 
    scanf("%d %d %d", &a, &b, &c); 
    if(a && b && c) {
        printf("Largest number is %d\n", largestNumber(a, b, c)); 
        printf("Smallest number is %d\n", smallestNumber(a, b, c)); 
    } else {
        printf("Please enter three integers.\n"); 
    }
    return 0; 
}

int largestNumber (int a, int b, int c) {
    int large = a;
    if (b > large && b > c) {
       large = b; 
       return large;
    }
    if (c > large) {
       large= c; 
       return large;
    } 
    else {
       large = a; 
       return large;
    }
    
}

int smallestNumber (int a, int b, int c) {
    int small = a; 
    if (b< small && b < c) {
       small= b; 
       return small;
    }
    if (c < small) {
       small= c; 
       return small;
    } else {
       small= a; 
       return small;
    }
}
