#include <stdio.h>

#define MAX 100

int binomialCoefficient(int n, int k) {
    int C[MAX][MAX];
    
    for (int i = 0; i <= n; i++) {
        for (int j = 0; j <= k; j++) {
            if (j == 0 || j == i)
                C[i][j] = 1;
            else
                C[i][j] = C[i-1][j-1] + C[i-1][j];
        }
    }
    
    return C[n][k];
}

int main() {
    int n, k;
    printf("Enter values for n and k: ");
    scanf("%d %d", &n, &k);
    
    if (k > n) {
        printf("Invalid input\n");
    } else {
        printf("Binomial Coefficient C(%d, %d) is %d\n", n, k, binomialCoefficient(n, k));
    }

    printf("\n\n\nRoshan    192210659\n");

    return 0;
}
![Screenshot 2024-09-10 124737](https://github.com/user-attachments/assets/a32c7120-3236-42d2-8e8f-2f3fd80a49eb)
