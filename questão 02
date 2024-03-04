#include <stdio.h>

int main()
{
    //Define o número de caracteres por linha.
    int caracteres_por_linha = 10;

    //Valida o valor de caracteres_por_linha.
    if (caracteres_por_linha <= 0){
        printf("Erro: o número de caracteres por linha deve ser positivo.\n");
        return 1;
    }

    //Imprime o cabeçalho da tabela.
    printf("Valores ASCII de 0 a 127:\n");

    //Laço para iterar de 0 a 127.
    for (int i = 0; i <= 127; i++){
        //Ignora os caracteres de controle.
        if (i >= 32 && i <= 126) {
            //Imprime o código ASCII e o caractere correspondente.
            printf("%3d: %c ", i, (char)i);
        } else {
            //Imprime espaços em branco.
            printf("%3d:   ", i);
        }

        //Verifica se é o final da linha.
        if ((i + 1) % caracteres_por_linha == 0){
            //Imprime uma nova linha.
            printf("\n");
        }
    }

    //Adiciona uma nova linha adicional para separar a saída do prompt de comando.
    printf("\n");

    return 0;
}
