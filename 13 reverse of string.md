#include <stdio.h>
#include <string.h>

void reverseString(char str[]) {
    int length = strlen(str);
    for(int i = length - 1; i >= 0; i--) {
        printf("%c", str[i]);
    }
    printf("\n");
}

int main() {
    char str[100];
    printf("Enter a string: ");
    gets(str); 
    printf("Reversed string: ");
    reverseString(str);
    printf("\n\n\nRoshan    192210659\n");

    return 0;
}
![Screenshot 2024-09-10 123637](https://github.com/user-attachments/assets/0c021e24-02a6-4c62-8ea2-67fe0f589e92)
