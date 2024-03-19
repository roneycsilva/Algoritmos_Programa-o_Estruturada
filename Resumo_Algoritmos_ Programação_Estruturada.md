# **Algoritmos e Programação Estruturada**
> Este resumo faz parte dos estudos realizados no curso de Análise e Desenvolvimento de Sistemas na Faculdade Anhanguera, unidade Santana

 Nele, apresentamos uma síntese do livro, enfatizando uma compreensão acessível a todos que buscam aprimorar seus conhecimentos ou satisfazer sua curiosidade.

- [Kleber Ricardi Rovai](https://www.escavador.com/sobre/4203036/kleber-ricardi-rovai#google_vignette/)
- [Marcio Aparecido Artero](https://www.escavador.com/sobre/5260515/marcio-aparecido-artero/)
- [Vanessa Cadan Scheffer](https://www.escavador.com/sobre/5952962/vanessa-cadan-scheffer/) 


 
## **Unidade 1º**
<div style="text-align: justify;">
O livro "Algoritmos e Programação Estruturada" convida os leitores a explorarem os fundamentos dos algoritmos, linguagens de programação e estrutura de programas de computador. Destaca-se uma empresa de tecnologia educacional que busca estagiários sem experiência para trabalhar em programação, com o leitor assumindo o papel de treinador desses estagiários. São apresentados conceitos, 
definições e aplicações de algoritmos, além de introduções aos componentes e estruturas em linguagem C. Após o treinamento, os estagiários serão capazes de reconhecer os conceitos básicos de algoritmos e linguagens de programação. As seções subsequentes abordam variáveis, prática de programação, operações e expressões para programas de computador.</div>

# **Seção 1º**
<div style="text-align: justify;">
Apresenta os conceitos de algoritmos e programação de forma didática. Um algoritmo é definido como uma sequência finita de passos que resolvem uma determinada tarefa. O objetivo é capacitar estagiários sem experiência em programação para trabalhar no desenvolvimento de sistemas. Como exercício, os estagiários são desafiados a criar um algoritmo para cadastrar dados pessoais de alunos, como nome, endereço, cidade e estado, e exibir esses dados na tela do computador. O algoritmo deve ser elaborado em linguagem natural, diagrama de blocos e pseudocódigo, visando estimular a compreensão e aplicação prática dos conceitos. Essa atividade demonstra como os algoritmos são fundamentais na criação de códigos de programação.<p>
</p>

A linguagem natural é uma forma de comunicação entre pessoas, podendo ser verbal, escrita ou gestual. É útil no desenvolvimento de aplicações computacionais, pois simplifica a descrição de problemas e soluções. Um exemplo prático é o cadastro de notas de alunos, onde o usuário entra com duas notas e o computador calcula a média, determinando se o aluno foi aprovado ou reprovado. Um algoritmo exemplar é o algoritmo euclidiano, criado por Euclides, para calcular o máximo divisor comum. <p>
</p>

1.	Início
2.	Entrar com o primeiro valor (nota do primeiro bimestre).
3.	Entrar com o segundo valor (nota do segundo bimestre).
4.	Realizar a soma do primeiro valor com o segundo.
5.	Realizar a divisão da soma dos valores por dois (média das notas dos bimestres).
6.	Armazenar o valor encontrado.
7.	Mostrar na tela o resultado da média.
8.	Se a média do aluno for maior ou igual a seis.
9.	O aluno será considerado aprovado.
10.	Senão está reprovado.
11.	Fim

Um outro exemplo de algoritmo que vale a pena citar de acordo com Piva Junior (2012) é o algoritmo euclidiano, Euclides, usando de sua sabedoria, criou um algoritmo para calcular o máximo divisor comum, o famoso “MDC” no qual pode ser resumida da seguinte forma:
1.	Dividir um número “a” por “b”, onde o resto é representado por “r”.
2.	Substituir a por b.
3.	Substituir b por r.
4.	Continuar a divisão de a por b até que um não possa ser mais dividido, então “a” é considerado o mdc.

<p align="center">
  <img width="500" height="300" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/5d046b64-c4a0-49eb-9972-53a03fd486a6" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>
</div>

<div style="text-align: justify;">
  O texto introduz o conceito de linguagem natural e sua proximidade com nossa linguagem cotidiana. Antes de explicar diagramas de blocos e pseudocódigo, aborda brevemente o conceito de variáveis e atribuições. Variáveis são elementos que podem variar e recebem valores através de atribuições. Por exemplo, "valor1 ¬8" significa que o valor "8" está sendo atribuído à variável "valor1". 
  O texto encerra convidando o leitor a entender o funcionamento dos diagramas de blocos, também conhecidos como fluxogramas, para continuar seus estudos de algoritmos.
</div>

# **Diagrama de blocos (fluxograma)**
<div style="text-align: justify;">
   diagrama de blocos como um conjunto de símbolos gráficos que representam ações específicas a serem executadas pelo computador. Destaca-se que o diagrama de blocos determina a linha de raciocínio usada pelo desenvolvedor para resolver problemas. Ao criar um diagrama de blocos, é importante que os símbolos utilizados estejam em harmonia e sejam de fácil compreensão. 
  Os símbolos foram padronizados pela ANSI para garantir a coerência dos diagramas de blocos. O texto segue para explicar os principais símbolos utilizados em um diagrama de blocos.
</div>
<p>
  </p>

> Quadro 1.1 | Descrição e significados de símbolos no diagrama de blocos

<p align="center">
  <img width="600" height="600" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/796acad4-25e8-4052-bac3-6b88dd076b57" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>
</div>

<div style="text-align: justify;">
  Ao utilizar os símbolos com as instruções em diagramas de blocos, o aprendizado e desenvolvimento da lógica para resolver problemas são incrementados. 
  O exemplo do Diagrama 1.1 apresenta a solução de um algoritmo usando diagrama de blocos como ilustração.
</div>

<p align="center">
  <img width="600" height="600" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/ddd21211-f0d5-4e8a-a3de-6cb7a350ba06" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>
</div>

Dicaspara construção de um Diagrama de bloco (fluxograma)

São: 

1. Estar atento aos níveis.
2. O diagrama de blocos (fluxograma) deve começar de cima para baixo e da esquerda para direita.
3. Ficar atento para não cruzar as linhas, principalmente as linhas de fluxos de dados.

O diagrama de blocos apresentado mostra a execução da média de dois valores.


Vejamos então as representações de cada passo do diagrama:
O símbolo terminal deu início ao diagrama de blocos.

O símbolo terminal deu início ao diagrama de blocos.
<p align="center">
  <img width="150" height="75" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/11284bb6-b80e-4bba-97cc-25983ea88f49" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>
</div>

O símbolo de processamento definiu as variáveis.
<p align="center">
  <img width="200" height="75" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/2a5358f9-9e4a-481f-b8b4-54f7a001b7c2" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>
</div>

O símbolo exibição mostra na tela o que o usuário deve fazer.
<p align="center">
  <img width="200" height="75" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/088789ca-8650-4be5-86bc-1d6c9211b2d3" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>
</div>

O símbolo de entrada manual libera para o usuário entrar com o primeiro valor.
<p align="center">
  <img width="200" height="75" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/c86ac434-83ef-4dc4-9089-6f646460083f" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>
</div>

O símbolo exibição mostra na tela o que o usuário deve fazer.
<p align="center">
  <img width="200" height="75" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/2d6a08cc-727f-4264-ba17-525edf0aec44" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>
</div>

O símbolo de entrada manual libera para o usuário entrar com o segundo valor.
<p align="center">
  <img width="200" height="75" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/99646992-25f2-419b-a8ac-bd97c6d07c9a" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>
</div>

O símbolo de processamento realiza as atribuições dos valores calculados para suas respectivas variáveis. A soma dos valores 1 e 2 será atribuída à variável soma. E o resultado da soma será dividido por 2 e atribuído à variável media.
<p align="center">
  <img width="200" height="75" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/d35ea489-e7d0-4016-85b0-97873142a16f" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>
</div>

O símbolo de exibição mostra na tela o resultado de cada valor calculado.
<p align="center">
  <img width="200" height="75" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/ffec2c16-e76b-464f-807f-a1b3fb71295a" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>
</div>

O símbolo de decisão define a condicional (verdadeiro ou falso) para a variável.
<p align="center">
  <img width="200" height="75" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/b13b99d1-236e-4870-ab2b-59aa42652611" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>
</div>

Se a condição for verdadeira, a resposta será “Aprovado”.
<p align="center">
  <img width="200" height="75" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/46bfdbbc-719e-4987-ba2f-eea4c9541b6e" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>
</div>

Se a condição for falsa, a resposta será “Reprovado”.
<p align="center">
  <img width="200" height="75" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/a230cfd1-6b03-4ed2-a935-70161e067ad5" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>
</div>

Finaliza o programa.
<p align="center">
  <img width="200" height="75" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/7f30722c-48d1-4266-abdc-b78aadcbcda9" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>
</div>

## **Pseudocódigo**
<div style="text-align: justify;">
   De acordo com Aguilar (2011), o pseudocódigo é uma ferramenta útil na programação, permitindo uma representação em linguagem próxima ao inglês ou português para facilitar a interpretação e o desenvolvimento de programas. 
  Os algoritmos na programação podem ser expressos por meio de pseudocódigos, visando alcançar a solução de problemas de forma clara e eficiente.
</div>
<p>
  </p>

É importante estar atento para algumas regras básicas quando utilizar pseudocódigos:
• Escolher um nome.
• Avaliar as variáveis, dar atenção aos seus tipos e características.
• Descrever de forma clara o que será armazenado e se as variáveis destinadas a essa informação estão corretas.
• Verificar se as instruções fazem sentido e se têm uma sequência lógica.
• Avaliar o resultado e quando pertinente, mostra-lo na tela.
• Finalizar o algoritmo.
<p>
  
</p>
O uso de pseudocódigo pode ser aplicado para qualquer linguagem
de programação?

Exemplo 

```c

calculo_media;
var
real: valor1, valor2, soma, media;
Início
escreva (“Digite o valor 1”);
leia valor1;
escreva (“Digite valor 2”);
leia valor2;
soma ¬ valor1 + valor2;
media ¬ soma/2;
escreva(“A media do aluno e:”; media);
se (media >=6)
então escreva(“Aluno Aprovado”);
senão escreva(“Aluno Reprovado”);
Fim se;
Fim.

``` 
## **Veja agora os comentários deste algoritmo:**

1. Linha “calculo_media” esse é o nome reservado para identificar o algoritmo.
2. Linha “Var”, indica a declaração das variáveis.
3. Linha São os nomes dados para as variáveis (valor1, valor2, soma, media), nesta linha também são definidos os tipos de variáveis (“real”, veremos com maior detalhe na próxima unidade do livro).
4. Linha inicia os procedimentos dos algoritmos (início).
5. Linha “escreva” é um comando de saída, este comando indica o que vai sair na tela do computador, geralmente o conteúdo do texto a ser mostrado fica entre aspas (“Digite valor 1”).
18
6. Linha “leia” é comando de entrada, o valor digitado é armazenado na variável (valor1).
7. Linha “escreva” é um comando de saída, este comando indica o que vai sair na tela do computador, geralmente o conteúdo do texto a ser mostrado fica entre aspas (“Digite valor 2”).
8. Linha “leia” é comando de entrada, o valor digitado é armazenado na variável (valor2).
9. Linha A adição das variáveis valor1 e valor2 é atribuído para variável soma (soma ¬ valor1 + valor2).
10. Linha Realiza o cálculo da média e atribui o valor encontrado na variável média.
(media ¬ soma/2).
11. Linha Escreve na tela o que está entre aspas. Escreva (“A media do aluno e:”; media). Perceba que a variável é colocada fora das aspas, para que seja representada pelo seu valor correspondente.
12. Linha Utiliza o resultado da média para criar uma condição verdadeira ou falsa: se (media >=6).
13. Linha Se o resultado da média for maior ou igual a seis (condição verdadeira), o computador escreve na tela “Aluno Aprovado”
14. Linha Se o resultado da média for menor que seis (condição falsa) o computador escreve na tela “Aluno Reprovado”.
15. Linha Encerra a condição (fim se).
16. Linha Encerra o algoritmo com a palavra “fim” e o ponto final.

<p></p>
Lembre-se, quando você escreve um algoritmo do tipo portugol, que é um pseudocódigo, é preciso escrever de forma clara para que as pessoas possam interpretar e, futuramente, possam passar para uma linguagem de programação.
<p></p>

> Veja abaixo um algoritmo escrito em pseudocódigo e executado em Visualg:

 ```c

algoritmo “media”
var
valor1, valor2, soma, media: real
inicio
19
Escreval(“Digite o valor da nota 1: “)
Leia (valor1)
Escreval(“Digite o valor da nota 2: “)
Leia (valor2)
soma <- (valor1 + valor2)
media <- (soma / 2 )
Escreval(“A media do aluno e:” media)
se media >=6 entao
escreval (“Aluno Aprovado média = “, media)
senao
escreval (“Aluno Reprovado média = “,media)
fimse
finalagoritmo

```  
<div style="text-align: justify;">
  Os parâmetros utilizados também são considerados um algoritmo do tipo português estruturado, ou seja, de fácil entendimento e interpretação.
O software do Visualg é gratuito e o seu download está disponível na internet (VISUALG, 2020).
 <p></p>
Manzano, Franco e Villar (2015) destacam os paradigmas de programação após estudarem algoritmos e suas formas de construção. Eles mencionam a programação estruturada, onde o algoritmo é desenvolvido como uma sequência linear de funções ou módulos, e a programação orientada a objetos, na qual o programador concebe o programa como uma coleção de objetos que interagem entre si.

</div>
<p>
  </p>

## **Pseudocódigo**
<div style="text-align: justify;">
   Após compreendermos os conceitos, aplicações e tipos de algoritmos, é crucial entender a relevância da linguagem de programação e suas variantes, assim como as perspectivas profissionais que a carreira de programador pode oferecer.
Conforme Marçula (2013 p. 170), a linguagem de programação (LP) pode ser concebida como um conjunto de termos (vocabulário) e um conjunto de normas gramaticais (para conectar esses termos) usados para direcionar o sistema de computação a executar tarefas específicas e, dessa forma, criar programas. Cada linguagem possui seu próprio conjunto de termos-chave e estruturas sintáticas.
 <p></p>
 
De acordo com Tucker (2010), assim como entendemos as línguas naturais usadas no cotidiano, a linguagem de programação é a comunicação de ideias entre o computador e as pessoas. O autor também observa que as primeiras linguagens de computador utilizadas foram as linguagens de máquina e a linguagem assembly, a partir da década de 1940. Desde então, muitas linguagens surgiram, e novos paradigmas de linguagem de programação foram desenvolvidos.
As definições dos paradigmas das linguagens de programação são descritas a seguir. Segundo Houaiss, Franco e Villar (2001, p. 329), “paradigma significa modelo, padrão. No contexto da programação de computadores, um paradigma é um modo, uma forma, um estilo de programar”. De acordo com Tucker (2010), um paradigma de programação está relacionado a um padrão de soluções de problemas, os quais, por sua vez, estão vinculados a uma determinada linguagem de programação. Tucker (2010) reconhece a evolução de quatro paradigmas de programação nas últimas três décadas:
 <p>
   </p>
   </div>
<p>
  </p>

  
+ **Programação imperativa**: considerada o paradigma mais antigo, que pode agrupar o programa e suas variáveis, juntamente com a abstração procedural, as atribuições, as sequências, os laços, os comandos condicionais e a manipulação de exceções como seus componentes de programação. Exemplos incluem COBOL, Fortran, C, Ada e Perl. <p></p>
+ **Programação orientada a objetos**: também conhecida na computação como (POO), é considerada uma coleção de objetos que interagem entre si, facilitando a programação. Exemplos incluem vSmalltalk, C++, Java e C#.<p></p>
+ **Programação funcional**: caracterizada por uma abordagem matemática, com cada função tendo um domínio e uma faixa. Exemplos incluem Lisp, Scheme, Haskell e ML.<p></p>
+ **Programação lógica**: é uma forma declarativa de programação, onde um programa pode modelar uma situação-problema declarando o resultado desejado, em vez de especificar como alcançá-lo. Exemplos incluem Prolog.<p></p>

Todas as linguagens de programação para criar um programa possuem uma sintaxe, que é a maneira como o programa é escrito. De acordo com Tucker (2010, p. 24), “[a] sintaxe de uma linguagem de programação é uma descrição precisa de todos os seus programas gramaticalmente corretos”.
Agora que compreendemos a importância de conhecer as linguagens de programação e suas aplicações, vamos explorar os componentes de um programa de computador.

<div style="text-align: justify;">
  Tucker (2010) compara a linguagem de programação à comunicação entre humanos, destacando que as primeiras linguagens de computadores foram as linguagens de máquina e assembly a partir da década de 1940. Ele também discute os paradigmas de programação, definindo-os como padrões de solução de problemas relacionados a determinadas linguagens. Tucker identifica quatro paradigmas principais: imperativo, orientado a objeto, funcional e lógico. Cada um possui características distintas e exemplos de linguagens associadas. Além disso, destaca a importância da sintaxe, que descreve a forma correta de escrever programas em linguagens de programação. Esses conceitos são cruciais para entender as linguagens de programação e suas aplicações na criação de programas de computador.
</div>
<p>
  </p>

## **Componentes de um programa de computador**
<div style="text-align: justify;">
 Conforme descrito por Damas (2016) e Aguilar (2011), envolve uma sequência de instruções para resolver um problema específico. Um programa pode ser desenvolvido em módulos distintos ou subprogramas. Para criar um programa, é necessário seguir algumas etapas:
</div>
<p>
  </p>

+ Definir e analisar o problema a ser solucionado.
+ Criar um algoritmo ou um diagrama de fluxo.
+ Realizar o pseudocódigo.

Para executar um programa é importante estar atento à sequência que os dados percorrem:

+ Entrada de dados: realiza as coletas de dados.
+ Processamento: os dados são transformados em informação.
+ Saída: onde todas as informações geradas pelo processamento de dados são apresentadas em um periférico.

Para criar um programa, é necessário definir as instruções a serem utilizadas na solução de um problema. Conforme Aguilar (2011), as sintaxes (ou instruções) devem ser escritas e armazenadas na memória do computador na ordem em que se espera que sejam executadas. Essas instruções podem ser lineares, ou seja, executadas sequencialmente, ou não lineares, sendo redirecionadas por instruções de bifurcação.

Veja um exemplo de instrução linear:
Instrução 1
Instrução 2
.
.
Instrução n
No caso de um programa não linear, ele pode se comportar da seguinte maneira.
Instrução 1
Instrução x
Instrução y
Instrução 2
.
.
Instrução n
Muito bem, a partir de agora você irá conhecer as sequências de instruções para criação de um programa de computador. Vamos lá!
No contexto geral ficaria assim:


1. Início do programa.
2. Definição das variáveis e de possíveis atribuições.
3. Instrução de leitura dos dados.
4. Instrução do formato de escrita.
5. Demais instruções e funções.
6. Fim do programa. <p></p>
Ou seja,

```c

Início
variáveis;
comando1;
comando2;
23
×
×
comandoN;
Fim.

```
Em algoritmos, a forma de escrever (maiúsculas e minúsculas) não acarretará em erros, porém, em linguagem de programação C é preciso diferenciar as palavras em letras maiúsculas e minúsculas.
Veja no Quadro 1.2 a estrutura básica de um algoritmo e de um programa em linguagem C.

<p align="center">
  <img width="500" height="250" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/918e7755-f74d-4101-96a1-1cbaad47e3af" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>
</div>

<div style="text-align: justify;">
 Quando iniciamos um programa na linguagem de programação C, segundo Manzano, Franco e Villar (2015), as primeiras linhas de programação são definidas pelas bibliotecas, também conhecidas como arquivos de cabeçalho.
Para inserir as bibliotecas no programa é necessário colocar #include (inclusão de um arquivo no programa fonte) e em seguida, entre os símbolos de menor “<” e maior “>” (quando se usa < e > o arquivo é procurado na pasta include) o nome da biblioteca.
Veja alguns exemplos de biblioteca em linguagem de programação C:
</div>
<p>
  </p>
 
- stdio – essa biblioteca é responsável pelas funções de entradas e saídas, como é o caso da função printf e scanf que vamos aprender mais à frente.<p></p>
Exemplo: #include \<s tdio.h>

- stdlib – essa biblioteca transforma as strings (vetores de caracteres) em números.
Exemplo: #include \<s tdlib.h>
- string – biblioteca responsável pela manipulação de strings.
Exemplo: #include\<s tring.h>
- time – biblioteca utilizada para manipulação de horas e datas.
Exemplo: #include<time.h>
- math – biblioteca utilizada para operações matemáticas.
Exemplo: #include<math.h>
- ctype – biblioteca utilizada para classificação e transformação de caracteres.
Exemplo: #include <ctype.h>
