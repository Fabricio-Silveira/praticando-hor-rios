# praticando-horarios

#include <stdio.h>
#include <stdlib.h>

int main()
{
    int horario_cinema = 90;
    int horario_atual = 60;

        if(horario_atual >= horario_cinema - 30){
            printf("Podemos entrar\n");
        }else if (horario_atual < horario_cinema + 30){
            printf("Ainda nao esta na hora\n");
        }
    return 0;
}
