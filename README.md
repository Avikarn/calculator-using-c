//calculator-using-c
#include<stdio.h>
int main()
{
float a,b;
char op;
printf("Enter the expression:");
scanf("%f%c%f",&a,&op,&b);

switch(op)
    {
    case'+':
    printf("%.1lf + %.1lf=%.1lf",a,b,a+b);
    break;
    case '-':
    printf("%f - %f=%f",a,b,a-b);
    break;
    case '*':
    printf("%f * %f=%f",a,b,a*b);
    break;
    case '/':
    printf("%f / %f=%f",a,b,a/b);
    break;

    default:
    printf("\nThe operator is not correct");
    }
}
