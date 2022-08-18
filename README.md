# Calculando-a-media
Calculando a media de 3 notas, P1,P2,trabalho.

#include <stdio.h>
#include <stdlib.h>

int main()
{
    float nota1,nota2,notatrabalho,media; //Declando as variaves, tipo float pois vamos considerar que alguns valores sejam decimais

    printf("\nDigite a nota da P1:"); //Imprimindo uma mensagem para o usuario interagir
    scanf("%f",&nota1); // Lendo a variavel

    printf("\nDigite a nota da P2:"); //Imprimindo uma mensagem para o usuario interagir
    scanf ("%f",&nota2); //Lendo a variavel

    printf("\nDigite a nota do trabalho:"); //Imprimindo uma mensagem para o usuario interagir
    scanf("%f",&notatrabalho); //Lendo a variavel

    media = (nota1+nota2+notatrabalho) /3; //Calculo da media

    printf ("Media do aluno:%.1f\n",media); //Imprimindo o resultado, media do aluno

    system("pause"); //Pausa da tela, somente para Windows

    return 0;
}
