#include <stdio.h>
#include <string.h>

int main() {
    char source[100], destination[100];
    printf("Enter the source string: ");
    fgets(source, sizeof(source), stdin);
    strcpy(destination, source);
    printf("Copied string: %s", destination);
    printf("\n\n\nRoshan    192210659\n");

    return 0;
}
![Screenshot 2024-09-10 123352](https://github.com/user-attachments/assets/d334083a-f216-4a72-840d-32e646665ffe)
