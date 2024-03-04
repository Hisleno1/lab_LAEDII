#include <stdio.h>

//Função para verificar se um número é primo
int isPrime(int n, int divisor){
    //Se o número for menor ou igual a 1, não é primo
    if (n <= 1){
        return 0; 
    } 
    //Se o divisor for 1, o número é primo
    if (divisor == 1){
        return 1; 
    }
    //Se o número for divisível pelo divisor, não é primo
    if (n % divisor == 0){
        return 0; 
    }
    //Chama recursivamente a função com um divisor menor
    return isPrime(n, divisor - 1);
}

int main()
{
    int num, retorno;
    //Solicita ao usuário que digite um número
    printf("Digite um número: ");
    //Lê o número digitado pelo usuário
    scanf("%d", &num);

    //Chama a função isPrime para verificar se o número é primo
    retorno = isPrime(num, num / 2);

    //Verifica o retorno da função e imprime se o número é primo ou não
    if (retorno == 0){
        printf("%d não é primo\n", num);
    }

    if (retorno == 1){
        printf("%d é primo\n", num);
    }
    return 0;
}
