# include <stdio.h>
 
int main()
{
    int  num, binary_value, decimal_value = 0, base = 1, remi;
 
    printf("Enter a binary number(1s and 0s) \n");
    scanf("%d", &num);
    binary_value = num;
    while (num > 0)
    {
        remi = num % 10;
        decimal_value = decimal_value + rem * base;
        num = num / 10 ;
        base = base * 2;
    }
    printf("The Binary number is = %d \n", binary_value);
    printf("Its decimal equivalent is = %d \n", decimal_value);
}
