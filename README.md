#include <stdio.h>
   int main() {
    char str1[100], str2[100];
    int i, j;
      printf(“25331A05D6\n”);
     printf("Enter two strings:\n");
    scanf("%s %s", str1, str2);
    for(i = 0; str1[i] != '\0'; i++);
    for(j = 0; str2[j] != '\0'; j++, i++) {
        str1[i] = str2[j];
    } str1[i] = '\0';
     printf("Concatenated string: %s\n", str1);
     return 0;
   }
