#include <stdio.h>
int main()
{
    int n;
    printf("Enter a number 1 to 5:");
    scanf("%d",&n);
    switch(n)
    {
    case 1:
    printf("Burger \nRs 129");
    break;
    case 2:
    printf("Sandwich \nRs 149");
    break;
    case 3:
    printf("Pizza \nRs 239");
    break;
    case 4:
    printf("Pasta \nRs 179");
    break;
    case 5:
    printf("French Fries \nRs 99");
    break;
    default:
    printf("Invalid");
    }
   
}
