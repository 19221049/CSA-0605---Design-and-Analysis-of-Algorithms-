#include <stdio.h>

int factorial(int n) {
    if (n == 0)
        return 1;
    return n * factorial(n - 1);
}

int main() {
    int num;
    printf("Enter a number: ");
    scanf("%d", &num);
    printf("Factorial of %d is %d.\n", num, factorial(num));

    printf("\n\n\nGnanesh P.C   192210492\n");
    return 0;
}
![Screenshot 2024-09-10 122159](https://github.com/user-attachments/assets/bda80ae0-daf9-48d5-b6dd-c3030b5d49d1)
