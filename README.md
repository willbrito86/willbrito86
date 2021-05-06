- 👋 Hi, I’m @willbrito86
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
willbrito86/willbrito86 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

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
	
