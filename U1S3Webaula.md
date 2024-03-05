# **Algoritmos e Programação Estruturada**
> Operações e expressões

Nesta webaula temos como objetivo apresentar os operadores matemáticos, relacionais e lógicos. 

<img align="right" alt="image_01" title="imagem shutterstock" alt="imagem shutterstock"
  src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/d81d3104-3961-4cf0-9f48-a267ccd5b095" width="310" height="250">       

  <div style=" height: 300px; margin: 15px; position: relative; display: block;" >
   <p style="word-wrap: break-word; " 

>**Sistemas computacionais**

Desde o momento em que você liga um computador (ou tablet, ou smartphone), centenas de processos são inicializados e passam a competir pelo processador para que possam ser executados e fazer a “mágica” do mundo digital acontecer. 

Todos os resultados desses sistemas são obtidos através do processamento de dados e nesta webaula começaremos a estudar os recursos que lhe permitirão implementar soluções com processamento.

Os sistemas computacionais são construídos para resolver os mais diversos problemas. Todos esses sistemas, independentemente da sua aplicação, são construídos em três partes: entrada, processamento e saída.

Nos três casos, a leitura dos dados é feita para um único fim: processamento e geração de informações e essa etapa é construída a partir da combinação de operações aritméticas, relacionais, lógicas e outras técnicas de programação.

&nbsp;</p>

> **Operadores aritméticos**

<img align="right" alt="image_01" title="Operadores aritméticos" alt="Operadores aritméticos" 
  src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/aa72a69a-d117-4fb6-aecb-77c10092ab82" width="450" height="250">       

  <div style=" height: 600; margin: 15px; position: relative; display: block;" >
   <p style="word-wrap: break-word; " 
 
Vamos começar a aprimorar nossos algoritmos através das operações aritméticas. Os operadores aritméticos podem ser classificados em unários ou binários (MANZANO, 2015)
  

&nbsp;</p>

  Quando trabalhamos com operadores, a ordem de precedência é muito importante. Segundo Soffner (2013), os operadores aritméticos possuem a seguinte ordem de execução:

|1° Parênteses.|
:--- |
|2° Potenciação e radiciação.|
|3° Multiplicação, divisão e módulo.|
|4° Soma e subtração.|

> **Operadores relacionais**
<img align="right" alt="image_01" title="Operadores relacionais" alt="Operadores relacionais" 
  src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/f35c2d37-7847-445b-8596-a7eb9b479124" width="450" height="350">       
  <div style=" height: 600; margin: 15px; position: relative; display: block;" >
   <p style="word-wrap: break-word; " 
 
Vamos começar a aprimorar nossos algoritmos através das operações aritméticas. Os operadores aritméticos podem ser classificados em unários ou binários (MANZANO, 2015)

&nbsp;</p>

  *Observe o código a seguir, de acordo com as entradas n1=5, n2=10 e n3=5*

º A instrução (n1 == n2) && (n1 == n3), mostrará se n1 é igual a n2  E(&&) n1 é igual a n3. No caso será impresso o valor 0 (falso), pois n1 e n2 são diferentes.

º A instrução (n1 == n2) || (n1 == n3), mostrará se n1 é igual a n2 OU(||) n1  é igual a n3. No caso será impresso o valor 1 (verdadeiro), pois, os valores de n1 e n3 são iguais.

º A instrução (n1 < n3) || (n1 > n2), mostrará se n1é menor que n3 OU (||) n1 é maior que n2. No caso será impresso o valor 0 (falso), pois, os valores de n1 e n3 são iguais e n1 é maior que n2.

Para realizar um teste prático, utilize a ferramenta [Online GDB](https://www.onlinegdb.com/), um compilador online em C. 

> **Operadores lógicos**

Além dos operadores relacionais, outro importante recurso para o processamento é a utilização de operadores lógicos, que possuem como fundamento a lógica matemática clássica e a lógica boolena (GERSTING, 2017). 

<img width="" height="" title="Operadores lógicos" alt="Operadores lógicos" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/028b01d3-c274-4e8e-901e-a7c42d7ea431" width="450" height="250">       

  <div style=" height: 600; margin: 15px; position: relative; display: block;" >
   <p style="word-wrap: break-word; " 
 &nbsp; </p>

Observe no código a seguir, que na linha 14 if (strcmp(login, "aluno01")==0 && strcmp(senha, "teste01")==0)utilizamos os operadores “==” e “&&”.

º O operador “==” compara se as strings de entradas em login é igual a “aluno01” e senha é igual a “teste01”.
º O operador “&&” verifica se o login e a senha correspondem os valores de entradas.
Para realizar um teste prático, utilize a ferramenta [Online GDB](https://www.onlinegdb.com/), um compilador online em C. 

> **Funções predefinidas**

Para facilitar o desenvolvimento de soluções em software, cada linguagem de programação oferece um conjunto de funções predefinidas que ficam à disposição dos programadores. Entende-se por função “um conjunto de instruções que efetuam uma tarefa específica.” (MANZANO, 2015, p. 153).

<div style="text-align: center;">
    <img width="" height="" title="Operadores lógicos" alt="Operadores lógicos" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/4276666b-f7b0-470b-be47-7645f98c02c3" width="450" height="250">
</div>

<div style="height: 600; margin: 15px; position: relative; display: block;">
    <p style="word-wrap: break-word;">
        &nbsp;
    </p>
</div>
Com esta webaula, exploramos as formas de armazenar temporariamente os dados em diversos tipos de variáveis e como podemos utilizar os operadores para realizar o processamento dos dados. Não se esqueça de recorrer ao livro didático para aprofundar os seus estudos.

