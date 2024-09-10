#include <stdio.h>

int gcd(int a, int b) {
    if (b == 0)
        return a;
    return gcd(b, a % b);
}

int main() {
    int num1, num2;
    printf("Enter two integers: ");
    scanf("%d %d", &num1, &num2);
    printf("GCD of %d and %d is %d.\n", num1, num2, gcd(num1, num2));

    printf("\n\n\nGnanesh PC   192210492\n");
    return 0;
}
![Screenshot 2024-09-10 121812](https://github.com/user-attachments/assets/3f8a4028-6b58-4756-9ea2-683160bec4db)
