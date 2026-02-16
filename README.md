# Btech-G2d-Aftab_45
c programs
#include <stdio.h>

int main() {
 int a;
 printf("enter first number");
 scanf("%d",&a);
 int b;
 printf("enter the second number");
 scanf("%d",&b);
 int c;
 printf("enter the third number");
 scanf("%d",&c);
 if(a>b&&a>c){
     printf("%d is greatest",a);
 }
 if(b>a&&b>c){
       printf("%d is greatest",b);
      }
   if(c>a&&c>b){
    printf("%d is greatest",c);
    
   }
    return 0;
}
