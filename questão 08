#include <stdio.h>

//Função para inverter os dígitos de um número inteiro
int inverteDigitos(int num){
  //Variável para armazenar o número invertido
  int invertido = 0;

  //Laço que itera enquanto o número original for maior que zero
  while (num > 0){
    //Multiplica o número invertido por 10 e adiciona o último dígito do número original
    invertido = invertido * 10 + num % 10;
    //Divide o número original por 10 para remover o último dígito
    num /= 10;
  }

  //Retorna o número invertido
  return invertido;
}

int main(void)
{
  //Variável para armazenar o número original
  int num = 0;

  //Solicita ao usuário o número original
  printf("Informe um número: ");
  scanf(" %d", &num);

  //Chama a função para inverter os dígitos do número
  int resultado = inverteDigitos(num);

  // Imprime o número com os dígitos invertidos
  printf("Número com os dígitos invertidos: %d\n", resultado);

  return 0;
}
