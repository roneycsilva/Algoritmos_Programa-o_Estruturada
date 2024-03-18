# **Algoritmos e Programação Estruturada**

> Estruturas de decisão condicional

Nesta webaula vamos ver sobre as estruturas de decisão e seleção.

## **Estrutura de repetição condicional while,do/while**

Assim como nas estruturas de decisão, as estruturas de repetição desenvolvem aplicações para a otimização do pensamento computacional e ao mesmo tempo, a agilidade nas soluções dos problemas de repetição.



### **Estrutura de repetição com teste no início – while**

Neste caso algo será repetidamente executado enquanto uma condição verdadeira for verificada, somente após a sua negativa essa condição será interrompida.

Na realização dessa condição, o comando iterativo "while”, que significa “enquanto” em português realiza o teste no início, antes de executar as ações programadas.

Sintaxe do comando “while” :

 <p></p>

    while (<condição>)
    {
    Comando 1;
    Comando 2;
    Comando n;
    } 

<p align="center">Fluxograma – repetição com teste no início”<p>


<p align="center">
  <img width="400" height="310" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/c649b2f2-f539-4ce6-8eec-b6aa24bec032" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>

Quando utilizamos teste no início, pode ocorrer o famoso loop (laço) infinito, que é quando um processo é executado repetidamente. Para que isso não aconteça, você poderá utilizar os seguintes recursos:

| Contador                                                                            | CIncremento e decremento                            | Acumulador                                                                                                                     | Condição de parada |
| :---:                                                                               |     :---:                                           |     :---:                                                                                                                      |                :---: |
| É utilizado para controlar as repetições, quando esta é determinada. | Trabalham o número do contador, seja ele, aumentando ou diminuindo.| Irá somar as entradas de dados de cada iteração da repetição, gerando um somatório a ser utilizado quando da saída da repetição.    | Utilizada para determinar o momento de parar quando não se tem um valor exato desta repetição.


No exemplo de repetição condicional a seguir, utilizando o comando while com teste no início, mostrará a palavra “PROGRAMA” dez vezes.


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


### **Estrutura de Repetição condicional com teste no final – do/while**

O laço “do-while” analisa a condição ao final do laço, ou seja, os comandos são executados antes do teste de condição. 

Neste caso, em específico, o usuário tem a possibilidade de digitar novamente uma nova informação (SCHILDT,1997).

Sintaxe do comando “do/while” :

 <p></p>

       Do
    {
    comandos; 
    } 
    while (condição);

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

O exemplo a seguir, realiza um programa que simula uma conta bancária (com tela de opções das transações. Ele repete uma entrada de dados até que determinada condição de saída seja atingida e, em seguida, acumule os valores digitados. Observe que foi utilizado o laço do-while para implementar o menu do programa, uma estrutura de repetição usando comparativo. Adaptado do livro do Soffner (2013). 

    #include <stdio.h>
    #include <stdlib.h>
    main() 
    {
    float soma=0; 
    float valor; 
    int opcao; 
    do {
    printf("\n Digite uma Operacao");
    printf("\n 1. Deposito"); 
    printf("\n 2. Saque"); 
    printf("\n 3. Saldo"); 
    printf("\n 4. Sair"); 
    printf("\n Opcao? "); 
    scanf("%d", &opcao);
    switch(opcao) {
         case 1: printf("\n Valor do deposito? "); 
                 scanf("%f", &valor); 
                 soma=soma+valor; 
                 break;
         case 2: printf("\n Valor do saque? "); 
                 scanf("%f", &valor); 
                 soma=soma-valor; 
                 break;
         case 3: printf("\n Saldo atual = R$ %.2f \n", soma); 
                 break; 
         default: if(opcao!=4)
    printf("\n Opcao Invalida! \n"); 
    }   
    }    
    while (opcao!=4); 
         printf("Fim das operacoes. \n\n"); 
         system("pause");
         return 0;
    }



| Pesquise mais!                                                                                                                                                                                                     |           
| :------                                                                                                                                                                                                              |                                                                                                
| O comando do-while pode ter várias aplicações. Veja o vídeo no YouTube “feito de aluno para aluno” sobre esse tema: <p></p>DE ALUNO PARA ALUNO. Programar em C - Como Utilizar "do while" - Aula 13. 24 out. 2012. |
