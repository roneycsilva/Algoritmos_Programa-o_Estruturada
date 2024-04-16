

# **Atividade U3S2 - Pós-aula**

<div style="text-align: justify; font-size: 18px; margin: 10px;">
<p> Escolha um exercício de uma prova de computação do ENADE que esteja relacionado ao assunto desta unidade de ensino e seção (U2S1), resolva à mão no caderno, e apresente na próxima aula. Endereço do website do Exame Nacional de Desempenho dos Estudantes (ENADE), contendo a provas no formato PDF para serem baixadas: 
    <p>https://www.gov.br/inep/pt-br/areas-de-atuacao/avaliacao-e-exames-educacionais/enade/</p></p>
</div>

<p style="text-align: justify; font-size: 15px; margin: 10px;">
   Questão
</p>

### QUESTÃO 25

<div style="text-align: justify; font-size: 18px; margin: 10px;">
<p>
Os sistemas digitais são componentes essenciais em uma ampla variedade de aplicações, desde dispositivos eletrônicos portáteis até sistemas de controle industrial. Um dos principais aspectos do projeto desse tipo de sistema é a descrição do circuito em uma Hardware Description Language (HDL), como Verilog ou VHDL. Essas linguagens permitem descrever o comportamento e a estrutura do circuito de forma abstrata, viabilizando a síntese e a simulação do sistema. 
  Um exemplo de circuito sequencial é o contador de 4 bits assíncrono, mostrado na figura a seguir,  o qual foi implementado utilizando flip-flops JK.
<p align="center">
  <img width="600" height="300" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/796709e3-da25-4283-81d8-4a9d67b62506" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>

  <div style="text-align: justify; font-size: 18px; margin: 10px;">
Nesse contexto, considere que um engenheiro proponha as duas traduções desse circuito em Verilog e VHDL, equivalentes entre si, conforme observado a seguir.

  ```c
  Verilog: 
  //----------------------------------------------
  module contador_4bits (
  ( input wire clk, 
  	input wire reset, 
  	output reg [1:0] count
  );
  	always @(posedge clk or posedge reset) begin 
  		if (reset) 
  			count <= 0; 
  	else
  		count <= count + 1; 
  	end
  endmodule
  //----------------------------------------------
  
  VHDL:
  //----------------------------------------------
  
  library ieee; 
  use ieee.std_logic_1164.all; 
  
  entity contador_4bits is  
  	port (     
  		clk : in std_logic;    
  		 reset : in std_logic;     
  		count : out integer range 0 to 3
  );
  end entity contador_4bits; 
  
  architecture behavioral of contador_4bits is 
  begin   
  	process(clk, reset) 
  	variable q : integer range 0 to 3; 
  begin     
  	if reset = '1' then       
  		q := 0;     
  	elsif rising_edge(clk) then       
  	 q := q + 1;     
  end if; 
  count <= q;  
  end process; 
  
  end architecture behavioral;
  
  //----------------------------------------------
  ```

    
Considerando as informações apresentadas, avalie as asserções a seguir e a relação proposta entre elas
I. Qualquer um dos códigos corresponde ao circuito contador de 4 bits mostrado na figura.<p></p>
PORQUE
  II. Ao atingir o valor máximo da contagem, o valor da saída será zerado no próximo ciclo de clock e o processo será reiniciado. <p></p>
</div>

 <p></p>
A respeito dessas asserções, assinale a opção correta

<p> </p>

- [ ] A. As asserçõe I e II  são proposições verdadeiras, e a II é uma justificativa correta da I.
- [ ] B. As asserções I e II são proposições verdadeiras, mas a II não é uma justificativa correta da I. 
- [ ] C. A asserção I é uma proposição verdadeira, e a II é uma proposição falsa. 
- [X] D. A asserção I é uma proposição falsa, e a II é uma proposição verdadeira.
- [ ] E. As asserções I e II são proposições falsas.
