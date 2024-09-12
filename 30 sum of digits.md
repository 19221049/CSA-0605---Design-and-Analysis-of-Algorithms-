#include <stdio.h>

int main() {
    int num, sum = 0, remainder;

    printf("Enter an integer: ");
    scanf("%d", &num);

    while (num != 0) {
        remainder = num % 10;
        sum += remainder;
        num /= 10;
    }

    printf("Sum of digits: %d\n", sum);
    printf("\n\n\nRoshan   192210659\n");

    return 0;
}
![Screenshot 2024-09-10 125854](https://github.com/user-attachments/assets/2777e77c-954e-4084-8617-9c6bddd1063f)
