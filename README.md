# algoritmo-em-C
#include <stdio.h>
#include <math.h>
int main(){
    int numero1,numero2;
    int soma,subtracao,multiplicacao,divisao;
    int num;
    int potencia;
    float numero;
    float raiz;
   
    printf("Nome: Ericson Santos Botelho Filho \n");
    printf("Curso: Analise e desenvolvimento de sistemas \n");
    printf("Universidade: La salle \n");
    printf("Matricula: 202221020 \n");
   
    printf("Digite um número para elevar ele a potencia: ");
    scanf( "%d",&num);
   
    printf("Digite um número para saber a raiz dele: ");
    scanf( "%f",&numero);
   
    potencia=pow(num,2);
    raiz=sqrt(numero);
   
    printf("O resultado da potenciacao é: %d\n",potencia);
    printf("O valor da raiz é: %.2f\n",raiz);
   
    printf("**Operaçoes aritmeticas de soma,subtraçao,multiplicacao e divisao**\n");
    printf("Digite o primeiro número: ");
    scanf("%d",&numero1);
   
    printf("digite o segundo número: ");
    scanf("%d",&numero2);
   
    soma=numero1+numero2;
    subtracao=numero1-numero2;
    multiplicacao=numero1*numero2;
    divisao=numero1/numero2;
   
    printf("numero1: %d\n",numero1);
    printf("numero2: %d\n",numero2);
    printf("soma: %d\n",soma);
    printf("subtracao: %d\n",subtracao);
    printf("Multiplicaçao: %d\n",multiplicacao);
    printf("divisao: %d\n",divisao);
    
    
         printf("Código adaptado do ebook pagina 33");
             
    return 0;
}
   
