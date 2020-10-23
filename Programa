#include <stdlib.h>
#include <stdio.h>

//programa de super fatorial
int fatorial(int valor){
    int f=1;
    while(valor>1)
    {
        f*=valor;
        valor=valor-1;
    }
    return f;
}

void SF(int valor, int *valor1)
{
    int i, aux=1, fat;

    for(i=2; i<=valor; i++)
    {
        fat=fatorial(i);
        aux = aux*fat;
    }
    *valor1=aux;
}

int main()
{
    int numero, sfat;

    printf("\n\n\t\tdigite o valor: ");
    scanf("%d", &numero);

    SF(numero, &sfat);
    printf("\n\n\t\t o super fatorial de %d eh %d", numero,sfat);
    return 0;
}
