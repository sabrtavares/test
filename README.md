// Troca-de-vetor-I

#include <stdio.h>
 
int main() {
 
//Variáveis
    int x,N[20],aux;
           
//Laço
for (x=0;x<20;x++){
        scanf("%d",&N[x]);
   }
for (x=0;x<10;x++){
        aux=N[x];
        N[x]=N[19-x];
        N[19-x]=aux;
    }
for (x=0; x<20;x++){
    printf("N[%d] = %d\n", x,N[x]);
    }
    return 0;
}
