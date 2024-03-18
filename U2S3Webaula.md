# **Algoritmos e Programação Estruturada**

> Estruturas de decisão condicional

Nesta webaula vamos ver a aplicação do laço “for”, ou seja, a estrutura de repetição com variáveis de controle.

## **Estrutura de repetição com variáveis de controle -for**

Assim como nas estruturas de decisão, as estruturas de repetição desenvolvem aplicações para a otimização do pensamento computacional e ao mesmo tempo, a agilidade nas soluções dos problemas de repetição.

O comando iterativo “for” que em português significa “para”, é geralmente usado para repetir uma informação por um número fixo de vezes, isto é, podemos determinar quantas vezes acontecerá a repetição. Mizrahi, 2008).

Sintaxe do comando “for”:

```c
   
for(inicialização; condição final; incremento) 
{
comandos;
}

``` 

<p align="center">Fluxograma – comando “for””<p>


<p align="center">
  <img width="400" height="310" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/087ac8ba-2532-4196-ae64-f0e7b6217a48" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>

Na aplicação do comando “for” há três expressões separadas por ponto e vírgula: inicialização, condição final e incremento.

<details>
  <summary>Inicialização</summary>
  Neste momento, coloca-se a instrução de atribuição. A inicialização é executada uma única vez antes de começar o laço</details>
  <p></p>
  
 <details>
  <summary>Condição final</summary>
  Realiza-se um teste que determina se a condição é verdadeira ou falsa; se for verdadeira, permanece no laço e, se for falsa, encerra o laço e passa para a próxima instrução. </details>
<p></p>
  
 <details>
  <summary>Incremento</summary>
  Parte das nossas explicações anteriores, em que é possível incrementar uma repetição de acordo com um contador específico, lembrando que o incremento é executado depois dos comandos. </details>


### **Exemplos**

A seguir, veremos alguns exemplos de utilização do comando for.

Como primeiro exemplo, iremos criar uma contagem regressiva de um número qualquer, digitado pelo usuário.

 <p></p>

```c
   
#include <stdio.h>
int main(void)
{
  int contador;
  printf("\nDigite um numero para contagem regressiva\n\n");
  scanf("%d", &contador);
    for (contador; contador >= 1; contador--)
  {
      printf("%d ", contador);
  }
  getch();
  return(0);
}

``` 
Pode-se usar o comando “break” dentro de um laço “for” para uma determinada condição, forçando assim, o término do laço. 

```c
   
#include <stdio.h> 
main()
{
int w; 
  for ( w = 1; w <= 15; w++ ) 
  {
    if ( w == 8 ) 
    { 
    break;
    } 
   printf ( “%d “, w ); 
 }
 printf( “\n \n Parar a condicao de repeticao w = %d \n”, w ); 
 return 0;
}

``` 
No exemplo a seguir, temos um programa que mostra uma sequência de números, onde x vai de 10 a 0 e y vai de 0 a 10.

Representação do comando for 


| for (x = 10,y = 0; x >= 0, y <= 10 ; x--,y++)                                                                    | 
| :---         |
| Na primeira expressão “x” tem o seu valor iniciado em “10” e “y” iniciado em “0”.                                | 
| Na segunda expressão o laço se repetirá enquanto n for maior ou igual a n e enquanto y for menor ou igual a 10.  | 
| Ao final da execução dos comandos do laço de repetição, x será decrementado de 1 e y será incrementado de 1.     |


   ```c
 #include <stdio.h>
      #include <stdlib.h>
      main() 
      {
          int cont=0; // foi definido na declaração da variável um valor inicial de "0"
          while (cont < 10) // Será executado enquanto a cont for menor que 10
          {
                printf("PROGRAMA \n"); 
                cont++; // será necessário incrementar um valor, para dar sequência no programa
           } 
          system("PAUSE");
          return 0;
      }
``` 
### **Estrutura de Repetição condicional com teste no final – do/while**

O laço “do-while” analisa a condição ao final do laço, ou seja, os comandos são executados antes do teste de condição. 

Neste caso, em específico, o usuário tem a possibilidade de digitar novamente uma nova informação (SCHILDT,1997).

Sintaxe do comando “do/while” :

 <p></p>

```c
     Do
    {
    comandos; 
    } 
    while (condição);
``` 

<p align="center">Fluxograma – repetição com teste no final
<p>


<p align="center">
  <img width="400" height="410" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets//61150519/a9910550-00f7-4fe2-a818-0b2b4d1bc1df" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>

O exemplo a seguir, realiza um programa que calcula a metragem quadrada de um terreno usando o teste no final para criar a opção de digitar novos valores sem sair do programa.

```c
      #include <stdio.h>
    main() {
    float metragem1,metragem2,resultado;
    int resp;
    metragem1 = 0;
    metragem2 = 0;
    resultado = 0;
      do
      {
        printf("C A L C U L O    D E   M E T R O S    Q U A D R A D O S");
        printf("\n \n Digite a primeira metragem do terreno: \n");
        scanf("%f",&metragem1);
        printf("\n Digite a segunda metragem do terreno: \n");
        scanf("%f",&metragem2);
        resultado = (metragem1 * metragem2);
        printf("\n \n O Terreno tem = %.2f M2 \n",resultado);
        printf("Digite 1 para continuar ou 2 para sair\n");
        scanf("%d", &resp);
      }while (resp==1);
    return 0;
    }
``` 
O exemplo a seguir, realiza um programa que simula uma conta bancária (com tela de opções das transações. Ele repete uma entrada de dados até que determinada condição de saída seja atingida e, em seguida, acumule os valores digitados. Observe que foi utilizado o laço do-while para implementar o menu do programa, uma estrutura de repetição usando comparativo. Adaptado do livro do Soffner (2013). 

```c
      #include <stdio.h>
    main() {
    float metragem1,metragem2,resultado;
    int resp;
    metragem1 = 0;
    metragem2 = 0;
    resultado = 0;
      do
      {
        printf("C A L C U L O    D E   M E T R O S    Q U A D R A D O S");
        printf("\n \n Digite a primeira metragem do terreno: \n");
        scanf("%f",&metragem1);
        printf("\n Digite a segunda metragem do terreno: \n");
        scanf("%f",&metragem2);
        resultado = (metragem1 * metragem2);
        printf("\n \n O Terreno tem = %.2f M2 \n",resultado);
        printf("Digite 1 para continuar ou 2 para sair\n");
        scanf("%d", &resp);
      }while (resp==1);
    return 0;
    }
``` 
   
| Pesquise mais!          |           
| :------                                                                                                                                                                                                              |                                                                                                
| O comando do-while pode ter várias aplicações. Veja o vídeo no YouTube “feito de aluno para aluno” sobre esse tema: <p></p>DE ALUNO PARA ALUNO. Programar em C - Como Utilizar "do while" - Aula 13. 24 out. 2012. |
