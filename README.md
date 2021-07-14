- 👋 Hi, I’m @VaibhaviBarapatre

Problem: Find LCM of 2 numbers.

Solution :

#include <stdio.h>
int main() 
{
    int n1, n2, max;
    printf("Enter two positive integers: ");
    scanf("%d %d", &n1, &n2);
    max = (n1 > n2) ? n1 : n2;

    while (1)
 {
        if (max % n1 == 0 && max % n2 == 0) {
            printf("The LCM of %d and %d is %d.", n1, n2, max);
            break;
        }
        ++max;
    }
    return 0;
}


Problem : Swap two numbers 

Solution :

#include <stdio.h> 

int main() 
{ 

    int x, y; 

    printf("Enter Value of x "); 

    scanf("%d", &x); 

    printf("\nEnter Value of y "); 

    scanf("%d", &y); 

  

    int temp = x; 

    x = y; 

    y = temp; 

  

    printf("\nAfter Swapping: x = %d, y = %d", x, y); 

    return 0; 
} 



