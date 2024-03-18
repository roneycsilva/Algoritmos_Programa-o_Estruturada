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
int main()
{
    int x,y;
    for(x = 10,y = 0; x >= 0, y <= 10; x--,y++) 
    {
        printf("x=%2d, y=%2d\n",x,y);
    }
    return 0;
}

```

### **Aplicações com vetores**

Vetor (array) é um tipo especial de variável capaz de armazenar diversos valores “ao mesmo tempo”, usando um mesmo endereço na memória. 

Sintaxe: tipo variavel [n] 

Na sintaxe acima [n] representa a quantidade de colunas ou linhas.

 <p></p>
<details>
  <summary>Clique para ver o código</summary>
  
```c
#include <stdio.h>

void main() {
    int num[5];
    printf("Entre com um numero\n");
    scanf("%d", &num[0]);
    printf("O valor digitado foi: %d", num[0]*2);
    getchar();
}
```
</details>

O exemplo a seguir mescla o comando for com while. O programa encontra a primeira posição para um determinado número inserido pelo usuário. 

```c
   
#include <stdio.h>
int main()
{
    int numero;
    int i;
    int posicao=0;
    int vetor[10];
    printf("Entre com o numero de ate 3 casas, diferente de zero, a ser procurado em um vetor de 10 posicoes: ");
    scanf("%d", &numero);
    //Preenche o vetor com numeros
    for(i=0;i<10;i++)
    {
        printf("\nEntre com o numero para a posicao %02d: ", i+1);
        scanf("%d", &vetor[i]);
    }
    //identifica a posicao do numero lido no vetor de entrada
    while(vetor[posicao] != numero)
    {
        posicao++;
    }
      // Imprime vetor
    for(i=0;i<10;i++)
    {
        printf("%03d ", vetor[i]);
    }
   // Imprime espaços até) a posição do numero, e em seguida um "*" sob o numero
    printf("\n ");
    for(i=0;i<posicao;i++)
    {
        printf("    ");
    }
    printf("*");
    return 0;
}

``` 

### **Instrução continue**

Uma instrução continue dentro de um laço possibilita que a execução de comandos corrente seja terminada, passando à próxima iteração do laço. 

No exemplo a seguir, temos um programa que percorrerá os números de 1 a 30 e neste percurso, irá testar se foi digitado algum número ímpar, caso seja ímpar o programa continua o teste até o fim do laço. 

```c

#include <stdio.h>
main()
{
int i;
   for (i=1; i <=100;i=i+1)
    if (i==30)
      break;
    else
      if (i%2==1)
       continue;
      else
       printf("%2d\n",i);
       printf("Termino do laco\n");
}   

```

### *Aplicações com matrizes**

Matrizes são arranjos de duas ou mais dimensões. 

Sintaxe: tipo variável [M][N] 

Onde, [M] representa a quantidade de linhas e [N] a quantidade de colunas.

O exemplo a seguir monta uma matriz 3 x 3, onde os valores são lançados de acordo com a linha e coluna. 

```c

#include <stdlib.h>
main()
{
 int linha,coluna;
 int matriz[3][3];
     for (linha=0; linha<3; linha++)
 {
     for (coluna=0; coluna<3;coluna++)
 {
     printf("Digitar os valores da matriz para: linha %d, coluna %d:  ",linha+1,coluna+1);
     scanf("%d", &matriz[linha][coluna]);
 }
 }
     printf("Veja a sua Matriz\n");
     for (linha=0;linha<=2;linha++)
 {
     for (coluna=0;coluna<3;coluna++)
        printf("%d\t",matriz[linha][coluna]);
        printf("\n\n");
 }
 system("pause");
 return 0;
}

``` 

<details>
  <summary>Resultado</summary>
  
<p align="center">
  <img width="400" height="410" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/dd34c323-4168-43f8-b926-ad03bdd66d71" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>
</details>


| Pesquise mais!     |
| ---      | 
| O vídeo referido a seguir traz uma dinâmica muito interessante na aplicação de vetores e matrizes. Realizado de “aluno para aluno”, apresenta uma revisão bem minuciosa da programação em linguagem C: | 
| DE ALUNO PARA ALUNO. **Programar em C** - Revisão Vetores/Matrizes - Aula 27. 21 nov. 2012.  | 


