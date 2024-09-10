#include <stdio.h>

int fibonacci(int n) {
    if (n == 0)
        return 0;
    else if (n == 1)
        return 1;
    else
        return (fibonacci(n - 1) + fibonacci(n - 2));
}

int main() {
    int n, i;
    printf("Enter the number of terms: ");
    scanf("%d", &n);
    for (i = 0; i < n; i++)
        printf("%d ", fibonacci(i));

    printf("\n\n\nGnanesh P.C   192210492\n");
    return 0;
}![Screenshot 2024-09-10 121356](https://github.com/user-attachments/assets/171e5ece-3e05-40ec-bf06-3ec772bd2bcc)
