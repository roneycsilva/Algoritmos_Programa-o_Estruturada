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

## **Estrutura condicional composta**

Sintaxe da instrução “if/else” (se/senão):

    if <(condição)>
    {
    <primeiro conjunto de comandos>;
    }
    else
    {
    <segundo conjunto de comandos>;
    }

### **Estrutura condicional simples**

Sintaxe da instrução “if” (se) utilizada na [Linguagem C](https://conteudo.avaeduc.com.br/202001/INTERATIVAS_2_0/ALGORITMOS_E_PROGRAMACAO_ESTRUTURADA/U2/S1/index.html), um compilador online em C.

 <p></p>

    #if <(condição)>
    {
    <conjunto de comandos>;
    }  

Fluxograma – função “if”


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
