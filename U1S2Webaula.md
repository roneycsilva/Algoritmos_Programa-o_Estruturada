# **Algoritmos e Programação Estruturada**
> Componentes e elementos de linguagem de programação 

Nesta webaula, vamos conhecer curiosidades sobre acontecimentos relacionados com o mundo da programação.

## **Foguete Ariane 5**
Você conhece o caso do foguete Ariane 5? 

Trata-se de um projeto da Agência Espacial Europeia de um primeiro voo não tripulado em 4 de junho de 1996, que custou bilhões de dólares e levou 10 anos para ser construído. 
O Foguete Ariane 5 explodiu 40 segundos após a decolagem em seu voo inaugural. Com isso, houve a destruição do foguete e de toda a carga que custava milhões de dólares, causando um enorme prejuízo financeiro e de tempo. 

**E tudo isso não aconteceu por uma falha mecânica, mas por um erro de programação.**

O programa que convertia um valor em float (ponto flutuante) para um inteiro de 16 bits (long int) recebeu como entrada um valor fora da faixa que suportava (“um estouro de inteiros”). 
Com esse bug, os computadores principais, inclusive o de backup, desligaram ao mesmo tempo, alegando um erro de execução (run time error). 
Por isso, é importante destacar que a declaração de uma variável de forma incorreta ou com tipos incompatíveis pode trazer erros muitas vezes catastróficos. Esse desastre mostra a importância da declaração de variáveis corretamente.
####
Algoritmo é uma sequência ordenada de passos que deve ser seguida para a realização de uma tarefa (BERG e FIGUEIRÓ, 1998).


<img align="right" alt="image_01" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/af0e228c-c7d9-4d0f-b258-8b3f930a718c" width="300" height="280">       

  <div style=" height: 300px; margin: 15px; position: relative; display: block;" >
   <p style="word-wrap: break-word; " 

>**BUG do milênio (Y2K)**

Você sabia que no fim do século XX houve uma grande mobilização no mundo e em uma comunidade programadores, devido ao chamado "bug do milênio”? 

Esse foi o nome dado para um provável acontecimento – que não se concretizou – na virada do ano de 1999 para 2000: havia o receio de que os sistemas da época não reconhecessem as datas do ano 2000 e retornassem para 1900. 







&nbsp;</p>

>**Mas por que isso?** 

Na época, recursos de memória eram caros e limitados – por exemplo, 1 MB de memória custava em torno de 700 dólares. Por isso, havia uma constante necessidade, por parte dos desenvolvedores, de economizar e otimizar espaço em memória. 
Assim, na década de 1960 as datas eram armazenadas, porém, eram interpretados apenas dois dígitos para o ano – os dois últimos dígitos.

No caso, o ano de 1999 seria interpretado apenas como “99” (dois últimos dígitos). Com isso, o receio era que, em vez de os sistemas reconhecerem o ano de 2000, o identificassem como ano de 1900, zerando os dois últimos dígitos na data. 

De fato, o problema não causou tantos impactos, pois muitos sistemas desenvolvidos na época já consideravam o ano com quatro dígitos. Porém, problemas pontuais ocorreram; alguns sites da época não reconheciam a data e mostravam a data “01/01/19100”, e houve falhas em terminais de ônibus e equipamentos de medição de radiação. 
Houve, também, investimentos de bilhões de dólares em medidas preventivas. 

Caso realmente tivesse se concretizado, esse acontecimento causaria um enorme prejuízo para bancos, com juros negativos, investidores e empresas poderiam indo à falência. 
Os sistemas de aeroportos e usinas nucleares poderiam entrar em colapso, causando quedas de aviões e vazamentos radioativos. 
Atualmente é improvável que esse tipo de problema ocorra, pois já temos alternativas de armazenamento em nuvem e recursos de memória mais baratos. 

>**VAMOS PRATICAR!**

Para exercitar um pouco, observe o código com o erro que se assemelha ao ocorrido no caso do foguete Ariane 5. Mostra que os erros de execução (run time error) são comuns quando se declara um vetor ou array com menor capacidade que o necessário para o problema. Nesse caso, o código é compilado sem erros, porém ocorrem problemas na execução. 

Para realizar um teste prático, utilize a ferramenta [Online GDB](https://www.onlinegdb.com/), um compilador online em C. 

Clique no botão Run para executar o código e observe possíveis runtime errors.



