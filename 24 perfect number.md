#include <stdio.h>

int main() {
    int num, i, sum = 0;

    printf("Enter a number: ");
    scanf("%d", &num);

    for(i = 1; i <= num / 2; i++) {
        if(num % i == 0) {
            sum += i;
        }
    }

    if(sum == num) {
        printf("%d is a perfect number.\n", num);
    } else {
        printf("%d is not a perfect number.\n", num);
    }

    printf("\n\n\nGnanesh P.C   192210492\n");

    return 0;
}
![Screenshot 2024-09-10 125145](https://github.com/user-attachments/assets/3671790b-c5bc-469b-93d4-eebbc01ccf8a)
