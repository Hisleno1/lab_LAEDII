#include <stdio.h>

//Função para desenhar uma sequência de asteriscos
void desenha(int numero)
{
  //Se o número for maior que zero
  if (numero > 0){
    //Chama a função recursivamente com o número anterior
    desenha(numero - 1);
    //Imprime um asterisco
    printf("*");
  }
}

int main(void)
{
  int num = 0; 

  //Solicita ao usuário que digite um número
  printf("Informe o número: ");
  
  //Lê o número digitado pelo usuário
  scanf("%d", &num);

  //Chama a função `desenha` com o número digitado como parâmetro
  desenha(num);

  //Imprime uma nova linha
  printf("\n");

  return 0;
}
