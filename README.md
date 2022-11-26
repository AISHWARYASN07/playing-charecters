# playing-charecters
In order to take a line as input, you can use scanf("%[^\n]%*c", s) Note: The statement: scanf("%[^\n]%*c", s); scanf("\n");
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() 
{

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */
    char ch;
    int i;
    char s[50];
    char sen[100];
    scanf("%c",&ch);
    scanf("%s",&s);
    scanf("\n)");
    scanf("%[^\n]%*c", sen);
    printf("%c\n",ch);
     printf("%s \n",s);
    // puts(sen);
    printf("%s",sen);
    
    return 0;
}
