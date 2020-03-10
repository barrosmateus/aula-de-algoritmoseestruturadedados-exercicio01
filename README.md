# aula-de-algoritmoseestruturadedados-exercicio01
#include <stdio.h>

int main()
{
    float preco, parcelas;
    
    printf("qual é o preço do produto? R$");
    scanf("%f", &preco);
    
    parcelas = preco / 5;
    
    printf(" A parcela é: R$ %f", parcelas);
}
