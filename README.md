- 👋 Hi, I’m @willbrito86, estou iniciando um Curso de Desenvolvimento de Sistema, pelo Senai : ).

#include <stdio.h>

// esse código vai pegar a quantidade de números citado pelo usuario e vai verificar cada um dele se é par ou impar
// código realizado no Devc++ em linguagem C++
int main(){
	
	int a, consult, c;	

	
	printf ("Quantos numeros deseja consultar\n?");
	scanf ("%d", &consult);
	
	for (c=0; c<consult; c++){
		printf("Qual o valor a ser verificado?\n");
		scanf("%d", &a);
		if(a%2==0){
			printf("Numero par\n");
		}else
			printf("NUmero impar\n");
		}
		}
	
