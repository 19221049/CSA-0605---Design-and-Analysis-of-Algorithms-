#include <stdio.h>

int isPrime(int num) {
    if (num <= 1) return 0;
    for (int i = 2; i * i <= num; i++) {
        if (num % i == 0) return 0;
    }
    return 1;
}

int main() {
    int limit;
    printf("Enter the limit: ");
    scanf("%d", &limit);

    printf("Prime numbers up to %d are:\n", limit);
    for (int i = 2; i <= limit; i++) {
        if (isPrime(i)) {
            printf("%d ", i);
        }
    }

    printf("\n\n\nRoshan   192210659\n");

    return 0;
}
![Screenshot 2024-09-10 124228](https://github.com/user-attachments/assets/9ff57ce4-9f01-4f50-8776-47037991fad8)
