#include <stdio.h>
#include <math.h>

int main() {
    int num, original, remainder, n = 0;
    float result = 0.0;

    printf("Enter an integer: ");
    scanf("%d", &num);
    original = num;

    while (original != 0) {
        original /= 10;
        ++n;
    }

    original = num;

    while (original != 0) {
        remainder = original % 10;
        result += pow(remainder, n);
        original /= 10;
    }

    if ((int)result == num)
        printf("%d is an Armstrong number.\n", num);
    else
        printf("%d is not an Armstrong number.\n", num);

    printf("\n\n\nGnanesh P.C   192210492\n");
    return 0;
}
![Screenshot 2024-09-10 121551](https://github.com/user-attachments/assets/fed546f2-47cf-4194-a5a1-c7f14d09f696)
