#include <stdio.h>

int main() {
    int rows, coef = 1, space, i, j;

    printf("Enter the number of rows: ");
    scanf("%d", &rows);

    for(i = 0; i < rows; i++) {
        for(space = 1; space <= rows - i; space++)
            printf("  ");

        for(j = 0; j <= i; j++) {
            if (j == 0 || i == 0)
                coef = 1;
            else
                coef = coef * (i - j + 1) / j;

            printf("%4d", coef);
        }
        printf("\n");
    }

    printf("\n\n\nRoshan   192210659\n");

    return 0;
}
![Screenshot 2024-09-10 125705](https://github.com/user-attachments/assets/3fa9f1a4-cc59-4071-8ba2-531e45ec61b9)
