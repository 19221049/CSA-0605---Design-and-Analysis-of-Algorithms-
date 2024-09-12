#include <stdio.h>

int main() {
    int n, i, min, max;
    printf("Enter the number of elements: ");
    scanf("%d", &n);
    int arr[n];
    printf("Enter %d numbers:\n", n);
    for(i = 0; i < n; i++) {
        scanf("%d", &arr[i]);
    }
    min = max = arr[0];
    for(i = 1; i < n; i++) {
        if(arr[i] < min)
            min = arr[i];
        if(arr[i] > max)
            max = arr[i];
    }
    printf("Minimum value: %d\n", min);
    printf("Maximum value: %d\n", max);
    printf("Sequence from minimum to maximum:\n");
    for(i = min; i <= max; i++) {
        printf("%d ", i);
    }
    printf("\n\n\n");
    printf("Roshan    192210659\n");
    return 0;
}
![Screenshot 2024-09-10 130004](https://github.com/user-attachments/assets/41fb351a-15d5-4480-bdd2-5a1239ef6b8c)
