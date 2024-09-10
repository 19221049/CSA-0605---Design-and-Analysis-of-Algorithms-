#include <stdio.h>
#include <limits.h>

int optimalBST(int keys[], int freq[], int n) {
    int cost[n][n];
    
    for (int i = 0; i < n; i++)
        cost[i][i] = freq[i];
    
    for (int L = 2; L <= n; L++) {
        for (int i = 0; i <= n - L; i++) {
            int j = i + L - 1;
            cost[i][j] = INT_MAX;
            int sum = 0;
            
            for (int k = i; k <= j; k++)
                sum += freq[k];
            
            for (int r = i; r <= j; r++) {
                int c = ((r > i) ? cost[i][r - 1] : 0) + 
                        ((r < j) ? cost[r + 1][j] : 0) + sum;
                if (c < cost[i][j])
                    cost[i][j] = c;
            }
        }
    }
    
    return cost[0][n - 1];
}

int main() {
    int keys[] = {10, 12, 20};
    int freq[] = {34, 8, 50};
    int n = sizeof(keys) / sizeof(keys[0]);

    printf("Cost of Optimal BST is %d\n", optimalBST(keys, freq, n));



    printf("\n\n\nRoshan   192210659\n");
    return 0;
}
![Screenshot 2024-09-10 124510](https://github.com/user-attachments/assets/a4e40789-1897-4556-b98a-7f4194c59fb9)
