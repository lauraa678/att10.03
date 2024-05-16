# att10.03

#include <stdio.h>
#include <stdlib.h>

int main() {
	float altura;
	float base;
	
	printf("Digite a base do retângulo: ");
	scanf("%f", &base);
	printf("Digite a altura do retângulo: ");
	scanf("%f", &altura);
	
	float area = base * altura;
	
	printf("A área desse retângulo mede: %f", area);
	
return 0;
}
