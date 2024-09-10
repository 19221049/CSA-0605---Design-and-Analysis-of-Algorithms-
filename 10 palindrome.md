#include <stdio.h>
#include <string.h>

int main() {
    char str[100], rev[100];
    printf("Enter a string: ");
    scanf("%s", str);
    strcpy(rev, str);
    strrev(rev);

    if (strcmp(str, rev) == 0)
        printf("%s is a palindrome.\n", str);
    else
        printf("%s is not a palindrome.\n", str);

    printf("\n\n\nRoshan    192210659\n");
    return 0;
}![Screenshot 2024-09-10 123247](https://github.com/user-attachments/assets/775efa49-f27f-4835-ae37-8045a935db16)
