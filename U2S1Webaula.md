# **Algoritmos e Programação Estruturada**

> Estruturas de decisão condicional

Nesta webaula vamos ver sobre as estruturas de decisão e seleção.

## **Estrutura de decisão condicional if/else (se/então)**

Para a solução de um problema que envolva situações podemos utilizar a instrução “if”, em português “se”, 
onde sua função é tomar uma decisão e criar um desvio dentro do programa, desta forma, podemos chegar a uma condição verdadeira ou falsa. 
Lembrando que a instrução pode receber valores em ambos os casos (MANZANO, 2013).

### **Estrutura condicional simples**

Sintaxe da instrução “if” (se) utilizada na [Linguagem C](https://conteudo.avaeduc.com.br/202001/INTERATIVAS_2_0/ALGORITMOS_E_PROGRAMACAO_ESTRUTURADA/U2/S1/index.html), um compilador online em C.

 <p></p>

    #if <(condição)>
    {
    <conjunto de comandos>;
    }  

<p align="center">Fluxograma – função “if”<p>


<p align="center">
  <img width="500" height="500" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/896559d1-7b75-4583-a95e-fa55eb31892a" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>

  No exemplo de condicional simples, será executado um teste lógico, onde, se o resultado for verdadeiro então ele trará uma resposta, caso contrário não retornará nada. 

No exemplo a seguir, não é considerado o “senão (else)”, simplesmente se a condição não for verdadeira ela não exibirá nada como resposta. 


      int main()
    {
    float idade; 
        printf("Digite sua idade: \n");
        scanf("%f", &idade);
     if (idade>=18) 
     {
 	        printf("Voce ja pode tirar sua carteira de Habilitacao, voce e maior de 18");
     }
     return 0;
 
    }


### **Estrutura condicional composta**

Sintaxe da instrução “if/else” (se/senão):


 <p></p>

    f <(condição)>
    {
    <primeiro conjunto de comandos>;
     }
    else
    {
    <segundo conjunto de comandos>;
    }

<p align="center">Fluxograma - funções “if” e  “else”<p>


<p align="center">
  <img width="500" height="500" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/0f1a6f87-3237-4be9-9bb3-b172057d0feb" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>

No exemplo de estrutura condicional composta a seguir, Maria e João estão se preparando para uma viagem, porém, se o orçamento final deles for igual ou maior que R$ 10.000,00 eles farão uma viagem internacional, senão deverão ficar com uma viagem nacional.


      #include <stdio.h>
      int main() {
      float orcamento;
      printf("Digite o valor do orcamento para viagem \n");
      scanf("%f", &orcamento);
      if (orcamento >=10000)
      {
      	printf("\n Joao e Maria possuem orçamento para uma viagem internacional, pois seu orcamento e de %f”, orcamento);
      }	
      else
      {
          printf("\n Joao e Maria irão optar por uma viagem nacional, seu orçamento ficou em %f", orcamento);
      }
      return 0;
      }

### **Estrutura condicional de seleção de casos "switch-case"**

A estrutura condicional de seleção de casos “switch-case” testa sucessivamente o valor de uma expressão contra uma lista de constantes inteiras ou de caractere”. Quando os valores são avaliados o comando é executado (SCHILDT,1997).

Sintaxe da instrução “switch-case” (seleção de casos):


 <p></p>

    switch (variável)
    {
    case constante1: 
    <comandos>
    break;
    case constante2: 
    <comandos>
    break;
    default: 
    <comandos>
    }

<p align="center">Fluxograma - funções “if” e  “else”<p>


<p align="center">
  <img width="500" height="500" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/02781092-acd0-4a41-befd-de76339d7479" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>

No exemplo de estrutura condicional de seleção de casos a seguir, é aplicado um desconto de acordo com a escolha de
uma cor específica pelo cliente.

    #include <stdio.h>
    int main() {
    	char x;
    	float valor,desc, total;
    	printf("\n Digite o valor da compra \n");
    	scanf("%f", &valor);
    	printf("\n Digite a letra que representa o seu desconto de acordo com a cor\n");
    	printf("a. azul\n");
    	printf("v. vermelho\n");
    	printf("b. branco\n");
    	printf(" Digite sua opcao:");
    	scanf("%s", &x);
    	switch(x)
    	{
    	case 'a':
    		printf("Voce escolheu azul, seu desconto sera de 30 por cento \n");
    		desc=valor*0.30;
    		total=valor-desc;
    		printf("O valor da sua compra e %.2f\n", total);
    		break;
    	case 'v':
    		printf("Voce escolheu vermelho, seu desconto sera de 20 por cento \n");
    		desc=valor*0.20;
    		total=valor-desc;
    		printf("O valor da sua compra e %.2f\n", total);
    		break;
    	case 'b':
    		printf("Voce escolheu branco, seu desconto sera de 10 por cento \n");
    		desc=valor*0.10;
    		total=valor-desc;
    		printf("O valor da sua compra e %.2f\n", total);
    		break;
    	default:
    		printf("opcao invalida\n");
    	}
    return 0;
    }

[Saiba Mais](#)
<details>
  <summary></summary>
  Algumas particularidades para o comando switch/case:<p></p> 
 * Caso nenhum dos valores seja encontrado, o comando default será executado.<p></p>
 * Os comandos são executados até o ponto que o comando break for localizado, que força a saída do laço de repetição.
</details>
<p>
 
</p>

## **Estrutura Condicional Encadeada**

Conhecida como **ifs aninhados**. É um comando if que é o objeto de outros if e else. Ou seja, sempre um comando else estará ligado ao comando if de seu nível de aninhamento (Schildt,1997).
Sintaxe:

    if (condição) comando;
    else
       if (condição) comando;
          else(condição) comando;
    .
    .
    .
         else  comando;

<p align="center">Fluxograma – estrutura condicional encadeada<p>


<p align="center">
  <img width="520" height="500" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/ba8080d1-5d84-4ced-b875-010012ff806e" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>

  No exemplo de estrutura condicional encadeada a seguir, será analisado os tipos de triângulo, partindo da premissa que ele deverá ser testado antes, para ver se forma ou não um triângulo.
  <p>
   </p>

       #include <stdio.h>
    #include <stdlib.h>
    int main( ) {
    int a, b, c;
    printf("Classificacao do triangulo: informe a medida dos lados apertando a Tecla ENTER para cada medida:\n");
    scanf("%d %d %d", &a, &b, &c);
    if (a< b + c && b< a +c && c < a + b)
    	{ 
    		printf("\n\n Dadas as medidas: %d, %d, %d, temos um triangulo", a, b, c);
    		if( a == b && a == c)
    		{
    		printf("Este e um triangulo EQUIILATERO! \n");
    		}
    			else
    				if ( a==b || a == c || b ==c)
    				{
    				printf("Este e um triangulo ISOSCELES!\n");
    				}
    					else
    					printf("Este e um triangulo ESCALENO! \n");
    	}
    		else
    		printf("\n\n As medidas fornecidas, %d,%d,%d nao formam um triangulo", a, b, c);
    return 0;
    }

 | Vimos as estruturas condicionais e de seleção. Pense nas possibilidades que você pode ter usando essas estruturas de tomadas de decisão “if-else”, “if-“else-if” e “switch-case”. Lembre-se que para cada caso poderá ter uma particularidade diferente em desenvolver um programa.    |
 | :------ |
