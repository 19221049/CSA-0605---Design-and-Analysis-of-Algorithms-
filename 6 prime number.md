#include <stdio.h>

int isPrime(int n) {
    if (n <= 1)
        return 0;
    for (int i = 2; i <= n / 2; i++) {
        if (n % i == 0)
            return 0;
    }
    return 1;
}

int main() {
    int num;
    printf("Enter a number: ");
    scanf("%d", &num);
    if (isPrime(num))
        printf("%d is a prime number.\n", num);
    else
        printf("%d is not a prime number.\n", num);

    printf("\n\n\nGnanesh P.C   192210492\n");
    return 0;
}
![Screenshot 2024-09-10 122334](https://github.com/user-attachments/assets/d77ea3f5-ccbd-4722-a46f-8fbc9ad74dde)
