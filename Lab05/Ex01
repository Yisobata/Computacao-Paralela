#include <stdio.h>
#include <stdlib.h>

int main(){
	int array[5] = {5, 10, 15, 20, 25};
	int mult;
	int i, j;
	printf("Array: [");
	for(i = 0; i < 5; i++){
		printf(" %d ", array[i]);
	}
	printf("]\n");
	printf("Digite o valor que ira multiplicar o array, caso selecione 0 iremos multiplicar por 4: ");
	scanf("%d", &mult);
	if(mult != 0){
		for (j = 0; j < 5; j++){
			array[j] *= mult;
		}
	}
	else{
		for (j = 0; j < 5; j++){
			array[j] *= 4;
		}
	}
	printf("Array: [");
	for(i = 0; i < 5; i++){
		printf(" %d ", array[i]);
	}
	printf("]\n");
}
