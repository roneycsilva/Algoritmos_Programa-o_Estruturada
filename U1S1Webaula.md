# **Algoritmos e Programação Estruturada**
> Conceitos de algoritmos e programação

Nessa webaula, vamos ver o conceito de algoritmo, como funcionam e quais suas aplicações dentro da programação.

## **Algoritmo**
Os algoritmos são as bases para criação de um programa de computador, onde diversas aplicações poderão ocorrer. Um algoritmo bem estruturado vai gerar um programa para solução de um problema que antes, parecia complexo. Todas as áreas estão voltadas para a tecnologia e são através de diversas formas de pensamentos que os algoritmos são realizados.

####
Algoritmo é uma sequência ordenada de passos que deve ser seguida para a realização de uma tarefa (BERG e FIGUEIRÓ, 1998).


<img align="right" alt="image_01" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/308e66c2-909f-4cd6-be9f-bc98201bf013" width="200" height="190">       

  <div style=" height: 300px; margin: 15px; position: relative; display: block;" >
   <p style="word-wrap: break-word; " 

Os algoritmos nortearão a descobrir qual o melhor percurso para solucionar um problema computacional.
A elaboração de algoritmos é um passo importante para o desenvolvimento de um programa de computador (ou software), pois, a partir da construção de algoritmos para a resolução de algum problema, é possível traduzir o algoritmo para alguma linguagem de programação.
   &nbsp;</p>


#### *A seguir, veja alguns exemplos de algoritmo:*

> Algoritmo para efetuar o cozimento de um arroz

|Solução|
|:--- |
|01. Acender o fogo;|
|02. Refogar os temperos;
|03. Colocar o arroz na panela;
|04. Colocar a água;
|05. Cozinhar o arroz;
|06. Abaixar o fogo;
|07. Esperar o ponto;
|08. Desligar o fogo;
|09. Servir o arroz.|

> Algoritmo para efetuar o cozimento de um arroz (mais detalhado)

 |Solução|
 |:--- |
 |01. Comprar o arroz;|
 |02. Analisar a qualidade;|
 |03. Realizar a pré-seleção para o cozimento;|
 |04. Preparar o tempero;|
 |05. Pegar a panela;|
 |06. Acender o fogo;|
 |07. Colocar os temperos na panela para refogar;|
 |08. Colocar os temperos na panela para refogar;|
 |09. Colocar a água na medida considerada ideal par a quantidade;|
 |10. Aguardar a água secar;|
 |11. Baixar o fogo;|
 |12. Fechar a panela com a tampa;|
 |13. Aguardo o ponto;|
 |14. Desligar o fogo;|
 |15. Servir o arroz.|

Assim, percebemos que não existe somente uma forma de realizar um algoritmo, podem ser criada outras formas e sequências para obter o mesmo resultado, ou seja, eles são independentes, porém, com a mesma finalidade de execução.

*Representação dos algoritmos*
O algoritmo é representado em três partes:

|Entrada  | Processamento             | Saída                      |
| -----   |     ----                  |                       ---- |
| Dados   | Execuçãos                 | Solução/Objetivo atingido  |
|ingredientes para o preparo do arroz)| (cozimento do arroz)       | (finalização do arroz - momento que será servido)|

> #### *Linguagem natural*
A linguagem natural na definição geral é uma forma de comunicação entre as pessoas de diversas línguas, ela pode ser falada, escrita, gesticulada entre outras formas de comunicação. A linguagem natural tem uma grande contribuição quando vamos desenvolver uma aplicação computacional, pois ela pode direcionar de forma simples e eficiente as descrições dos problemas e suas soluções (SANTOS, 2001).
 <div style=" height: 300px; margin: 15px; position: relative; display: block;" >
   <p style="word-wrap: break-word; " 

   Para reforçar os conceitos de linguagem natural podemos ver como exemplo o cadastro de notas de alguns alunos de um curso. 

|*Solução*                                                    | 
| :---                                                        |
| 1. Início;                                                  |
| 2. Entrar com o primeiro valor (nota do primeiro bimestre); |
| 3. Entrar com o segundo valor (nota do segundo bimestre);   |
| 4. Realizar a soma do primeiro valor com o segundo;         |
| 5. Realizar a divisão do total dos valores por dois (média das notas dos bimestres);|
| 6. Armazenar o valor encontrado;|
| 7. Mostrar na tela o resultado da média;|
| 8. Se a média do aluno for maior ou igual a seis;|
| 9. O aluno será considerado aprovado;|
| 10. Senão está reprovado;|
| 11. Fim.|

Entrar com o primeiro valor (nota do primeiro bimestre);
Entrar com o segundo valor (nota do segundo bimestre);
Realizar a soma do primeiro valor com o segundo;
Realizar a divisão do total dos valores por dois (média das notas dos bimestres);
Armazenar o valor encontrado;
Mostrar na tela o resultado da média;
Se a média do aluno for maior ou igual a seis;
O aluno será considerado aprovado;
Senão está reprovado;
Fim.

*Problema:*
O usuário deverá entrar com dois valores (as notas) e o computador retorna o resultado da média destes valores (média das notas). 
**Perceba que a linguagem natural é muito próxima da nossa linguagem.**|
|---|

&nbsp;</p>
<div style="margin: 350px; position: relative; display: block;" >
   <p style="word-wrap: break-word;"> 
Para reforçar os conceitos de linguagem natural podemos ver como exemplo o cadastro de notas de alguns alunos de um curso. 
Outro exemplo é o algoritmo para calcular o máximo divisor comum, o famoso “MDC”: 
> 1. Dividir um número “a” por “b”, onde o resto é representado por “r”
> 2. Substituir a por b
> 3. Substituir b por r
> 4. Continuar a divisão de a por b até que um não possa ser mais dividido, então “a” é considerado o mdc.
De acordo com a solução, o resultado fica: 
MDC (480,130) = 10
&nbsp;</p>

| a     | b     | R     |
|:---   |:---:  |  ---: |
| 480   | 130   | 90    |
| 130   | 90    | 40    |
| 90    | 40    | 10    |
| 40    | 10    | 0     |
| 10    | 0     |       |

> *Variáveis e Atribuições*

As *variáveis* como o próprio nome sugere, é algo que pode sofrer variações, ou seja, estão relacionadas a identificação de uma informação. Exemplos: valor1, nome.

A *atribuição* (← ) tem a função de indicar valores para as variáveis, ou seja, atribuir informação para variável. Exemplos:

**Valor  ← 8**
**Valor 1 ← marcio**

Significa que o número “8” está sendo atribuído para variável  “valor1”  e que o texto “marcio” está atribuído para variável “ nome”.

> *Diagrama de Blocos (Fluxograma)*

Diagrama de blocos é um conjunto de símbolos gráficos, onde cada um desses símbolos representa ações específicas a serem executadas pelo computador. Determina a linha de raciocínio utilizada pelo programador para resolver problemas. Os símbolos dos diagramas de bloco foram padronizados pela ANSI (Instituto Norte Americano de Padronização). 

A seguir, veja a descrição dos principais símbolos utilizados em um diagrama de blocos, de acordo com Manzano (2015):

<p align="center">
  <img width="520" height="300" alt="image_01" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/0ede048f-8533-40cd-85e6-8ad4eed513b2">
</p>     

<p align="center">
  <img width="520" height="300" alt="image_01" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/cb429bf2-1dc4-44f8-b346-e43f112cec55">
</p>

<p align="center">
  <img width="520" height="300" alt="image_01" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/3fd26770-af2c-40e1-b625-41188d09b75f">
</p>

<p align="center">
  <img width="800" height="500" alt="image_01" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/223aeccb-f7a1-4b17-a251-9fa6ee6f9461">
</p>      

> *Pseudocódigo*

O pseudocódigo é considerado uma ferramenta que pode auxiliar a programação, ela pode ser escrita em palavras similares ao inglês ou português para facilitar a interpretação e desenvolvimento de um programa (AGUILAR, 2011).

Exemplo de pseudocódigo que calcula a média das notas dos alunos de um curso:

```pascal
1. programa calculo_media;

2. var
3.     valor1, valor2, soma, media: real;

4. Início

5.     escreva('Digite o valor 1');
6.     leia(valor1);

7.     escreva('Digite valor 2');
8.     leia(valor2);

9.     soma := valor1 + valor2;

10.    media := soma / 2;

11.    escreva('A media do aluno e: ', media);

12.    se (media >= 6) então
13.        escreva('Aluno Aprovado');
14.    senão
15.        escreva('Aluno Reprovado');
16.    Fim se;

17. Fim.
```

Exemplo de algoritmo escrito em pseudocódigo e executado em Visualg :

```pascal
algoritmo "media"

var

            valor1, valor2, soma, media: real

inicio

            Escreval("Digite o valor da nota 1: ")

            Leia (valor1)

            Escreval("Digite o valor da nota 2: ")

            Leia (valor2)

            soma 
←
 (valor1 + valor2)

            soma 
←
 (soma / 2 )

            soma 
←
 (soma / 2 )

            Escreval(“A media do aluno e:” media)

            se media >=6 entao

                        escreval ("Aluno Aprovado média = ", media)

                        senao

                        escreval ("Aluno Reprovado média = ",media)

            fimse

Finalgoritmo
```
Perceba que os parâmetros utilizados também são considerados um algoritmo do tipo português estruturado, ou seja, de fácil entendimento e interpretação.

Paradigmas de programação
Após os estudos de algoritmos e as suas formas de construções, Manzano (2015) coloca em destaque os paradigmas de programação, que são caracterizados pelos paradigmas da:

| Programação estruturada | Programação Orientada a Objetos |
| --- | --- |
| Onde o algoritmo é construído como sequência linear de funções ou módulo. | Onde o programador abstrai um programa como uma coleção de objetos que interagem entre si. |

Os algoritmos são as bases para criação de um programa de computador, onde diversas aplicações poderão ocorrer. Um algoritmo bem estruturado vai gerar um programa para solução de um problema que antes, parecia complexo. Todas as áreas estão voltadas para a tecnologia e são através de diversas formas de pensamentos que os algoritmos são realizados.

