#include <stdio.h>

int linearSearch(int arr[], int n, int x) {
    for (int i = 0; i < n; i++) {
        if (arr[i] == x) {
            return i;
        }
    }
    return -1;
}

int main() {
    int arr[] = {10, 20, 30, 40, 50};
    int n = sizeof(arr) / sizeof(arr[0]);
    int x = 30;
    
    int result = linearSearch(arr, n, x);
    if (result == -1)
        printf("Element not found\n");
    else
        printf("Element found at index %d\n", result);
    
    printf("\n\n\nRoshan    192210659\n");
    return 0;
}
![Screenshot 2024-09-10 130917](https://github.com/user-attachments/assets/afc55a56-7f51-444e-98f9-77264d316ed5)
