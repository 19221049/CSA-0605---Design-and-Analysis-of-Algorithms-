#include <stdio.h>

int main() {
    int n, i;
    printf("Enter number of elements: ");
    scanf("%d", &n);
    int arr[n];
    printf("Enter elements: ");
    for (i = 0; i < n; i++)
        scanf("%d", &arr[i]);

    int largest = arr[0];
    for (i = 1; i < n; i++) {
        if (arr[i] > largest)
            largest = arr[i];
    }

    printf("Largest element is %d.\n", largest);

    printf("\n\n\nGnanesh PC   192210492\n");
    return 0;
}
![Screenshot 2024-09-10 122014](https://github.com/user-attachments/assets/8f47bfbd-baf6-4827-978c-bddf2a867c1c)
