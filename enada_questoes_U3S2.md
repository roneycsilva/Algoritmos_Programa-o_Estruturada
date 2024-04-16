

# **Atividade U3S2 - Pós-aula**

<div style="text-align: justify; font-size: 18px; margin: 10px;">
<p> Escolha um exercício de uma prova de computação do ENADE que esteja relacionado ao assunto desta unidade de ensino e seção (U2S1), resolva à mão no caderno, e apresente na próxima aula. Endereço do website do Exame Nacional de Desempenho dos Estudantes (ENADE), contendo a provas no formato PDF para serem baixadas: 
    <p>https://www.gov.br/inep/pt-br/areas-de-atuacao/avaliacao-e-exames-educacionais/enade/</p></p>
</div>

<p style="text-align: justify; font-size: 15px; margin: 10px;">
   Questão
</p>

### QUESTÃO 24

<div style="text-align: justify; font-size: 18px; margin: 10px;">
<p>
Um determinado sistema embarcado possui uma porta paralela de 8 bits, na qual cada pino pode ser configurado individualmente como interface de entrada ou de saída. A direção de cada pino da porta é definida pelo bit correspondente do registrador de direção de 8 bits PORT_DIR da seguinte forma:  valor 0 para configuração como entrada e valor 1 para configuração como saída. 
  Os bits de entrada da porta são armazenados no registrador PORT_IN e os bits de saída da porta são armazenados no registrador PORT_OUT, ambos de 8 bits. Os pinos que correspondem ao nibble (conjunto de 4 bits) menos significativo da porta de I/O são conectados aos seguintes dispositivos externos: alarme (SPK1), chave 2 (CH2), LED (LED1) e chave 1 (CH1), conforme a figura a seguir.<p></p>

<p align="center">
  <img width="500" height="250" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/bb292145-b6d0-440f-b3a2-860113ff5065" width="250" height="75">
  <div style="height: 75px; margin: 2px; position: relative; display: block; text-align: center;">
</div>
</p>
<p>
  </p>

  <div style="text-align: justify; font-size: 18px; margin: 10px;">
Considere que uma tensão VDD na porta corresponda ao valor lógico 1 e que uma tensão próxima a 0 V corresponda ao valor lógico 0.<p></p>
    I. O nibble menos significativo do registrador PORT_DIR deverá ser carregado com o valor 9 (decimal) pelo software do sistema para configuração adequada da porta de I/O. <p></p>
    II. Quando ambas as chaves (1 e 2) estiverem fechadas simultaneamente, o registrador PORT_IN possuirá o valor binário X1X0 no nibble menos significativo (X significa irrelevante). <p></p>
    III. Para acionar o alarme e o LED, simultaneamente, o registrador PORT_OUT deverá ser carregado com o valor binário 1X0X no nibble menos significativo (X significa irrelevante)..</p>
</div>

 <p></p>
É correto o que se afirma em 
<p> </p>

- [ ] A. I apenas. 
- [ ] B. II apenas 
- [ ] C. I e III apenas. 
- [X] D. II e III apenas
- [ ] E. I, II e III.
