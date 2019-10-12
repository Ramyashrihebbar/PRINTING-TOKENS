# PRINTING-TOKENS
#include <stdio.h>
int main()
{
    int i;
    char s[1000];
    printf("enter a sentence\n");
    scanf("%[^\n]%*c",s);
    for(i=0;s[i]!='\0';i++)
    {
        printf("%c",s[i]);
        if(s[i]==' ')
        {
            printf("\n");
        }
    }
}
