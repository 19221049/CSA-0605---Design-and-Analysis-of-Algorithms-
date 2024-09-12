#include <stdio.h>

void generateFactors(int n) {
    printf("Factors of %d are: ", n);
    for (int i = 1; i <= n; i++) {
        if (n % i == 0) {
            printf("%d ", i);
        }
    }
    printf("\n");
}

int main() {
    int n = 36;
    generateFactors(n);
    
    printf("\n\n\nRoshan    192210659\n");
    return 0;
}
![Screenshot 2024-09-10 130738](https://github.com/user-attachments/assets/a9794da6-1e0e-4341-9da6-42aee0c1e60c)
