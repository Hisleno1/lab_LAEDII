#include <stdio.h>

//Função para calcular o MDC (Máximo Divisor Comum) de dois números inteiros
int mdc(int a, int b)
{
    //Verifica se o segundo número é igual a zero
    if (b == 0){
        //Se for, retorna o primeiro número, pois é o MDC
        return a;
    } else {
        //Caso contrário, chama recursivamente a função mdc com b e o resto da divisão de a por b
        return mdc(b, a % b);
    }
}

int main(void)
{
    int a, b;

    //Solicita ao usuário que informe dois números inteiros
    printf("Informe dois números inteiros:\n");
    //Lê os dois números informados pelo usuário
    scanf(" %d %d", &a, &b);

    //Chama a função mdc para calcular o MDC dos números informados e imprime o resultado
    printf("MDC(%d, %d) = %d\n", a, b, mdc(a, b));

    return 0;
}
