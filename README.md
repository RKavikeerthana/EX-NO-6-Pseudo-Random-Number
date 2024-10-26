# EX-NO-6-Pseudo-Random-Number

## DATE:

# AIM

Implementation of Pseudorandom Number Generation Using Standard library

# PROGRAM
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() 
{
    int count, min, max;
    printf("*****Pseudo-Random-Number*****\n");
    printf("\n");
    printf("KAVI KEERTHANA R-212222100022");
    printf("\n");
    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &count);
    printf("Enter the minimum value: ");
    
    scanf("%d", &min);
    printf("Enter the maximum value: ");
    scanf("%d", &max);
    srand(time(NULL));
    printf("Pseudorandom numbers:\n");   
    for (int i = 0; i < count; i++) 
    {
        int random_number = (rand() % (max - min + 1)) + min;
        printf("%d\n", random_number);
    }
    return 0;
}
```




# OUTPUT
![image](https://github.com/user-attachments/assets/052fd3a2-20e2-4d44-8e1b-f5430ed52037)



# RESULT
Thus Pseudorandom Number Generation Using Standard library has been executed successfully

