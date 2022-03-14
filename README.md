# kawanquestao05
Kawanquestao05
#include <stdlib.h>  
#include <locale.h>
 
 
float valor_numerico();

int main() {
	setlocale(LC_ALL, "Portuguese_Brazil: ");

	valor_numerico();
} 

float valor_numerico() {

	int valor_numerico; printf("\nDigite um numero:");
	scanf("%d", &valor_numerico);

	if(valor_numerico < 0) {
	 printf("\nEste numero: Negativo");

} 
 	else {
	printf("\nEste numero: Positivo");
    }
}
