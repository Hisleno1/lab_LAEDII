#include <stdio.h>

//Função de Ackermann (A)
int A(int m, int n){
    //Verifica se m é igual a 0
    if (m == 0){
        //Caso base: retorna n + 1
        return n + 1;
    } 
    //Verifica se m é maior que 0 e n é igual a 0
    else if (m > 0 && n == 0){
        //Caso base: chama recursivamente A com m - 1 e 1
        return A(m - 1, 1);
    } 
    //Verifica se m e n são ambos maiores que 0
    else if (m > 0 && n > 0){
        //Caso recursivo: chama recursivamente A com m - 1 e A(m, n - 1)
        return A(m - 1, A(m, n - 1));
    }
}

//Função para calcular e imprimir os resultados de A(x, y) para x < a e y < b
void calcularA(int a, int b)
{
    //Imprime uma mensagem indicando os limites de x e y
    printf("Resultados para A(x, y) onde x < %d e y < %d:\n", a, b);

    //Laço para percorrer os valores de x
    for (int x = 0; x < a; x++){
        //Laço para percorrer os valores de y
        for (int y = 0; y < b; y++){
            //Imprime o resultado de A(x, y)
            printf("A(%d, %d) = %d\n", x, y, A(x, y));
        }
    }
}

int main()
{
    int a, b;

    //Solicita ao usuário que digite dois inteiros a e b
    printf("Digite dois inteiros a e b:\n");

    //Lê os valores digitados pelo usuário

    scanf("%d %d", &a, &b);

    //Chama a função para calcular e imprimir os resultados de A(x, y)
    calcularA(a, b);
    
    return 0;
}
