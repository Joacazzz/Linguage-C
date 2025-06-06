
#include <stdio.h>
#include<conio.h>
#include<time.h>
#include<stdlib.h>
//#define tamanho 15


 int  main(){ 
 int Vetor[15], i=1;
 int x=0;
 
	srand(time(NULL));
	
	while ( i <= 15){
	    
		Vetor[x] = rand() % 9 + 1;
	    
	if(Vetor[x]  % 2 == 0){
		printf("casa %d = %d par |", i, Vetor[x]);
	}else{
		printf("casa %d = %d impar |", i, Vetor[x]);
	}
	x++;
     i++;	
	}
     return 0;
	
}
