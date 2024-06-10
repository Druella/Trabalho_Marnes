#include <stdio.h>

int main(){

  float peso, alt, imc;

  printf("digite o peso: ");
  scanf("%f", &peso);

  printf("digite a altura: ");
  scanf("%f", &alt);

  imc = peso / (alt * alt);

  if(imc < 18.5){
    printf("%.2f\n", imc);
    printf("abaixo do peso");
  }else if(imc > 18.5 && imc < 24.9){
    printf("%.2f\n", imc);
    printf("peso normal");
  }else if(imc > 25 && imc < 29.9){
    printf("%.2f\n", imc);
    printf("excesso de peso");
  }else if(imc > 30 && imc < 34.9){
    printf("%.2f\n", imc);
    printf("obesidade classe 1");
  }else if(imc > 35 && imc < 39.9){
    printf("%.2f\n", imc);
    printf("obesidade classe 2");
  }else if(imc >= 40){
    printf("%.2f\n", imc);
    printf("obesidade classe 3");
  }else{
    printf("erro");
  }
}
