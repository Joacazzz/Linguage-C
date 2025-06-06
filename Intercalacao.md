#include <stdio.h>
#include<conio.h>
#include<time.h>
#include<stdlib.h>

int main(){
	int Vetor[10], VetorII[10], i=0, i2=0, VetorIII[20];

	srand(time(NULL));
	while ( i < 10){
		Vetor[i] = rand() % 100 + 1;
        VetorII[i] = rand() % 100 + 1;
       printf("%d e o numero dois %d\n", Vetor[i], VetorII[i]);
	   i++; 
		
    }
    i=0;
    while( i2 < 20){
	VetorIII[i2] = Vetor[i];
	VetorIII[i2+1] = VetorII[i];
	printf("%d %d\n", VetorIII[i2], VetorIII[i2+1]);
	i2+=2;
	i++;	

    }

}
