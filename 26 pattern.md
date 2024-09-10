#include <stdio.h>

int main() {
    int n = 4;

    for (int i = 1; i <= n; i++) {
        for (int j = 1; j <= n - i; j++) {
            printf("   ");
        }
        for (int j = 1; j <= i; j++) {
            printf("%d  ", j);
        }
        printf("\n");
    }

    printf("\n\n\nRoshan   192210659\n");

    return 0;
}
![Screenshot 2024-09-10 125504](https://github.com/user-attachments/assets/6fd00cab-ea11-467d-92fe-3f36110f4915)
