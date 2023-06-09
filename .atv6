# Capitulo-4manzano
Letra A

#include<stdio.h>
#include<stdlib.h>

int main() {
    int A, B, maior, menor, diferenca;

    printf("Digite os valores de A e B: ");
    scanf("%d%d", &A, &B);


    maior = (A > B) ? A : B;
    menor = (A < B) ? A : B;

    diferenca = maior - menor;

    printf("A diferença entre o maior e o menor valor e: %d\n", diferenca);
    system("pause");

    return 0;
}

Letra B

#include <stdio.h>
#include <stdlib.h>

int main() {
    int N;

    printf("Digite um valor inteiro: ");
    scanf("%d", &N);

    if (N < 0) {
        N = -N;
    }

    printf("O valor lido como positivo é: %d\n", N);

    return 0;
    system("pause");
}

Letra C

#include <stdio.h>
#include <stdlib.h>

int main() {
    float N1, N2, N3, N4, MD;

    printf("Digite as 4 notas do aluno: ");
    scanf("%f%f%f%f", &N1, &N2, &N3,&N4);

    MD = (N1 + N2 + N3 + N4) / 4;

    printf("Média obtida: %.2f\n", MD);

    if (MD >= 5) {
        printf("Aprovado\n");
    } else {
        printf("Reprovado\n");
    }

    return 0;
    system("pause");
}

Letra D

#include <stdio.h>
#include <stdlib.h>
int main() {
    float N1, N2, N3, N4, MD1, NE, MD2;

    printf("Digite as 4 notas do aluno: ");
    scanf("%f%f%f%f", &N1, &N2, &N3, &N4);

    MD1 = (N1 + N2 + N3 + N4) / 4;

    printf("Média obtida: %.2f\n", MD1);

    if (MD1 >= 7) {
        printf("Aprovado\n");
    } else {
        printf("Digite a nota do exame: ");
        scanf("%f", &NE);

        MD2 = (MD1 + NE) / 2;

        printf("Nova média obtida: %.2f\n", MD2);

        if (MD2 >= 5) {
            printf("Aprovado em exame\n");
        } else {
            printf("Reprovado\n");
        }
    }

    return 0;
}

Letra E

#include <stdio.h>
#include <stdlib.h>
#include <math.h>

int main() {
    float A,B,C,delta,x1,x2;
    

    printf("Digite os valores de A, B e C: ");
    scanf("%f%f%f", &A, &B, &C);

    delta = B * B - 4 * A * C;

    if (delta < 0) {
        printf("Não há solução real.\n");
    } else if (delta > 0) {
        x1 = (-B + sqrt(delta)) / (2 * A);
        x2 = (-B - sqrt(delta)) / (2 * A);
        printf("Há duas soluções reais e diferentes:\n");
        printf("x1 = %.2f\n", x1);
        printf("x2 = %.2f\n", x2);
    } else {
        x1 = -B / (2 * A);
        printf("Há apenas uma solução real:\n");
        printf("x = %.2f\n", x1);
    }

    return 0;
    system("pause");
}

Letra F

#include <stdio.h>
#include <stdlib.h>

int main() {
    int A, B, C;

    printf("Digite os valores de A, B e C: ");
    scanf("%d%d%d", &A, &B, &C);

    

    
    if (A > B) {
        
        int temp = A;
        A = B;
        B = temp;
    }

    if (B > C) {
        
        int temp = B;
        B = C;
        C = temp;
    }

    if (A > B) {
        
        int temp = A;
        A = B;
        B = temp;
    }

    printf("Valores em ordem crescente: %d, %d, %d\n", A, B, C);

    return 0;
    System("pause");
}

Letra G

#include <stdio.h>
#include <stdlib.h>

int main() {
    int A, B, C, D;

    printf("Digite os valores de A, B, C e D: ");
    scanf("%d%d%d%d", &A, &B, &C, &D);


    printf("Valores divisíveis por 2 e 3:\n");

    if (A % 2 == 0 && A % 3 == 0) {
        printf("%d\n", A);
    }

    if (B % 2 == 0 && B % 3 == 0) {
        printf("%d\n", B);
    }

    if (C % 2 == 0 && C % 3 == 0) {
        printf("%d\n", C);
    }

    if (D % 2 == 0 && D % 3 == 0) {
        printf("%d\n", D);
    }

    return 0;
    system("pause");
}

Letra H

#include <stdio.h>
#include <stdlib.h>

int main() {
    int A, B, C, D;

    printf("Digite os valores de A, B, C e D: ");
    scanf("%d%d%d%d", &A, &B, &C, &D);


    printf("Valores divisíveis por 2 e 3:\n");

    if (A % 2 == 0 || A % 3 == 0) {
        printf("%d\n", A);
    }
    else{printf("Valor de A nao divisível por 2 ou 3\n");}

    if (B % 2 == 0 || B % 3 == 0) {
        printf("%d\n", B);
    }
    else{printf("Valor de B nao divisível por 2 ou 3\n");}
    if (C % 2 == 0 || C % 3 == 0) {
        printf("%d\n", C);
    }
    else{printf("Valor de C nao divisível por 2 ou 3\n");}
    if (D % 2 == 0 || D % 3 == 0) {
        printf("%d\n", D);
    }
    else{printf("Valor de D nao divisível por 2 ou 3\n");}    
    return 0;
    system("pause");
}

Letra I

#include <stdio.h>
#include <stdlib.h>

int main() {
    int A, B, C, D, E, maior, menor;
    
    printf("Digite os valores de A, B, C, D e E: ");
    scanf("%d", &A, &B, &C, &D, &E);

    maior = A;
    menor = A;

    if (B > maior) {
        maior = B;
    }
    if (C > maior) {
        maior = C;
    }
    if (D > maior) {
        maior = D;
    }
    if (E > maior) {
        maior = E;
    }

    if (B < menor) {
        menor = B;
    }
    if (C < menor) {
        menor = C;
    }
    if (D < menor) {
        menor = D;
    }
    if (E < menor) {
        menor = E;
    }

    printf("Maior valor: %d\n", maior);
    printf("Menor valor: %d\n", menor);

    return 0;
    system("pause");
}

Letra J

#include <stdio.h>
#include <stdlib.h>

int main() {
    int valor;

    printf("Digite um valor inteiro: ");
    scanf("%d", &valor);

    if (valor % 2 == 0) {
        printf("O valor %d é par.\n", valor);
    } else {
        printf("O valor %d é ímpar.\n", valor);
    }

    return 0;
    system("pause");
}


Letra K

#include<stdio.h>
#include<stdlib.h>


int main() {
    int valor;

    printf("Digite um valor inteiro: ");
    scanf("%d", &valor);

    if (valor >= 1 && valor <= 9) {
        printf("O valor está na faixa permitida.\n");
    } else {
        printf("O valor está fora da faixa permitida.\n");
    }

    return 0;


    system("pause");
}

Letra L

#include<stdio.h>
#include<stdlib.h>

int main() {
    int valor;

    printf("Digite um valor inteiro: ");
    scanf("%d", &valor);

    if (!(valor > 3)) {
        printf("O valor é %d.\n", valor);
    }

    return 0;
    system("pause");
}

Letra M

#include<stdio.h>
#include<stdlib.h>

int main() {
    char n[50];
    char sexo;

    printf("Digite o seu nome: ");
    scanf("%s", n);

    printf("Digite o seu sexo (M/F): ");
    scanf(" %c", &sexo);

    if (sexo == 'M') {
        printf("Ilmo. Sr. %s\n", n);
    } else if (sexo == 'F') {
        printf("Ilma. Sra. %s\n", n);
    } else {
        printf("Sexo informado inválido.\n");
    }

    return 0;
    system("pause");
}

Letra N

#include<stdio.h>
#include<stdlib.h>

int main() {
    int A, B, C, soma;
   

    printf("Digite os valores de A, b e C: \n");
    scanf("%d%d%d", &A, &B, &C);

    soma = A + B + C;

    if(soma >= 100) {
        printf("O valor da soms dos valores e: %d\n", soma);
    }
    else{
        printf("A soma é monor que 100");
    }
}

Letra O

#include<stdio.h>
#include<stdlib.h>

int main(){
    int n, M;

    printf("Insira qualquer numero inteiro: ");
    scanf("%d", &n);

    M = n * 2;

    if(M>30) {
        printf("O resultado da multiplicaçao e: %d\n", M);
    }
    else{
        printf("O resultado é menor que 30");
    }
    return 0;
    system("pause");

}


