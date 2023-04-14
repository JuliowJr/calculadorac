#include <stdio.h>

void main(void) {
    
    int valor;
    int a,b, result;
    
    printf("1 - Somar\n");
    printf("2 - Subtrair\n");
    printf("3 - Multiplicar\n");
    printf("4 - Dividir\n");
    printf("5 - SAIR\n");
    scanf("%d",&valor);
    
    if(valor==1) {

    printf("escolha um numero:");
    scanf("%d",&a);
    printf("\nescolha outro numero:");
    scanf("%d",&b);
    result=a+b;
    printf("O resultado da soma é:%d",result);
    }
    if(valor==2) {

    printf("escolha um numero:");
    scanf("%d",&a);
    printf("\nescolha outro numero:");
    scanf("%d",&b);
    result=a-b;
    printf("O resultado da subtração é:%d",result);
    }
    if(valor==3) {

    printf("escolha um numero:");
    scanf("%d",&a);
    printf("\nescolha outro numero:");
    scanf("%d",&b);
    result=a*b;
    printf("O resultado da multiplicação é:%d",result);
    }
    if(valor==4) {

    printf("escolha um numero:");
    scanf("%d",&a);
    printf("\nescolha outro numero:");
    scanf("%d",&b);
    result=a/b;
    printf("O resultado da divisão é:%d",result);
    }
   
}
