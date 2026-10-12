# day-42
my c langauge pratices 
#```c
#include <stdio.h>

int main()
{
    FILE *fp;

    fp = fopen("data.txt", "w");

    if (fp == NULL)
    {
        printf("File not created");
        return 1;
    }

    printf("File created successfully");

    fclose(fp);

    return 0;
}
```
