# Calculator
Performs all the mathematical operations of a calculator;
#include<stdio.h>
#include<math.h>
int main(){
    float n1,n2;
    char ch;
    scanf("%f %f %c",&n1,&n2,&ch);
    switch(ch){
        case '+':printf("%.2f",n1+n2);
        break;
        case '-':printf("%.2f",n1-n2);
        break;
        case '/':printf("%.2f",n1/n2);
        break;
        case '*' : printf("%.2f",n1*n2);
        break;
    } return 0;
}
