
#include <unistd.h>
#include <stdio.h>

static void ft_strmatrix (char *str, int usec)
{
    int i;

    i = 0;
    while (str[i])
    {
        write(1, &str[i], 1);
        i++;
        usleep(usec);
    }
}

int main (int argc, char **argv)
{
int i = 0;
int istr = 0;

if (argc != 2)
   {
    printf("Un argument a la fois ;)\n");
    return(0);
   }
    ft_strmatrix("Copie le texte qui va apparaitre ci-dessous\n\n\n", 50000);
    while (argv[1][i] != '\0')
    //while (str[istr] != '"' && str[i + 1] != '"')
        //istr++;
    {
        printf("@printf \"");
        printf("%c",argv[1][i]);
        printf("\"");
            if (argv[1][++i])
            {
                printf(" && sleep 0.02 && printf \"");
                printf("%c",argv[1][i]);
                printf("\"");
            }
            if (argv[1][++i])
            {
                printf(" && sleep 0.02 && printf \"");
                printf("%c",argv[1][i]);
                printf("\"");
                printf(" && sleep 0.02");
                printf("\n");
            }
        i++;
    }
    printf("\n");
    ft_strmatrix("Merci d'avoir utiliser le script,\n\nEn cas de problème dans la sortie n'oublie pas de rajouter un \\n à la fin de l'argument.\n\n", 11111);    
return (0);
}
