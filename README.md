# Ling.Prog-2021
Linguagem de Programação
Exemplo_1
#include <stdio.h>


int main(void) {


  //Declarações de variaveis
float e_E1, e_R1, e_R2;
float s_I, s_VR1, s_VR2;

//entrada velocidade inicial
printf("Valor da fonte:");
scanf ("%f",&e_E1);

//entrada do tempo
printf("Valor de R1:");
scanf ("%f",&e_R1);

//entrada do valor da acelaração
printf("Valor de R2:");
scanf ("%f",& e_R2);

//atribuição: vf= v0+a.t

s_I = e_E1 / (e_R1 + e_R2);
 
 if (s_I == 0)
 {
   printf("Erro de Calculo:");
 }

else {
 
printf("s_I: %f [A]\n",
s_I);
}
  return 0;
}
