# Estrutura-de-Dados-2

#include <stdio.h>

int main() {
    int vetor[10] = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9};
    int i, temp;

    for (i = 0; i < 5; i++) {
        temp = vetor[i];
        vetor[i] = vetor[9 - i];
        vetor[9 - i] = temp;
    }
    
    // o "for" acima é responsável por realizar a inversão dos elementos de acordo com suas posições iniciais no vetor
    // onde o primeiro elemento troca com o ultimo, o segundo elemento troca com o penúltimo, e assim por diante. O numero
    // 5 foi escolhido como condição de parada por ser metade do numero de elementos do vetor definido ( 10 ).
 
    printf("Vetor invertido:\n");
    for (i = 0; i < 10; i++) {
        printf("%d ", vetor[i]);
    }
    
    // o "for" acima é responsável por imprimir o vetor invertido

    return 0;
}

Código dinamico:

#include <stdio.h>
#include <stdlib.h>

int main() {
    int n;
    scanf("%d", n);
    int vetor[n];
    int i, temp;
    
    for(i = 0; i < n; i++){
        scanf("%i", vetor[n]);
    }

    for (i = 0; i < n/2; i++) {
        temp = vetor[i];
        vetor[i] = vetor[ (n - 1) - i];
        vetor[(n - 1) - i] = temp;
    }
    printf("Vetor invertido:\n");
    for (i = 0; i < n; i++) {
        printf("%i ", vetor[n]);
    }
    
    return 0;
}
