#include <stdio.h>

int containerLoader(int weights[], int n, int capacity) {
    int total = 0;
    for (int i = 0; i < n; i++) {
        if (total + weights[i] <= capacity) {
            total += weights[i];
        } else {
            break;
        }
    }
    return total;
}

int main() {
    int weights[] = {10, 20, 30, 40, 50};
    int n = sizeof(weights) / sizeof(weights[0]);
    int capacity = 100;
    int result = containerLoader(weights, n, capacity);
    printf("Maximum weight loaded: %d\n", result);
    
    printf("\n\n\nRoshan    192210659\n");
    return 0;
}
![Screenshot 2024-09-10 130651](https://github.com/user-attachments/assets/a20dd8fc-b5ec-47e1-ad90-a21bb8974717)
