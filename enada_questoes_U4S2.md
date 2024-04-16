

# **Atividade U4S2 - Pós-aula**

<div style="text-align: justify; font-size: 18px; margin: 10px;">
<p> Escolha um exercício de uma prova de computação do ENADE que esteja relacionado ao assunto desta unidade de ensino e seção (U2S1), resolva à mão no caderno, e apresente na próxima aula. Endereço do website do Exame Nacional de Desempenho dos Estudantes (ENADE), contendo a provas no formato PDF para serem baixadas: 
    <p>https://www.gov.br/inep/pt-br/areas-de-atuacao/avaliacao-e-exames-educacionais/enade/</p></p>
</div>

<p style="text-align: justify; font-size: 15px; margin: 10px;">
   Questão
</p>

### QUESTÃO 30

<div style="text-align: justify; font-size: 18px; margin: 10px;">
<p>
Considere que, para melhorar o desempenho de sistemas computacionais, projetistas de hardware decidam aumentar o número de processadores em vez de aumentar a frequência de clock. Dessa forma, surge a necessidade de utilizar softwares que explorem o paralelismo. Um problema típico encontrado no desenvolvimento desse tipo de software é a dependência de dados. Nesse contexto, considere que dois processadores precisem realizar, simultaneamente, o acesso a uma mesma matriz A. Com base nas informações apresentadas, com relação aos trechos de código em linguagem C apresentados a seguir, assinale a opção que apresenta uma situação de conflito de dados.<p></p>



- [ ] A. Processador 1 <p></p>
      int a = &A [0] [0]; <p></p>
      Processador 2: <p></p>
      int b = &A[0] [0];
      
- [ ] B. Processador 1 <p></p>
     *A[0] [0] = 10; <p></p>
      Processador 2: <p></p>
      *A[0][1] = 20;
      
- [ ] C. Processador 1 <p></p>
      *A[0] [0] = 10; <p></p>
      Processador 2: <p></p>
      int b = &A[0] [0];
      
- [ ] D. Processador 1 <p></p>
      int a = &A[0][0]; <p></p>
      Processador 2: <p></p>
      *A[0][0] = 20;
      
- [X] E. Processador 1 <p></p>
      *A[0][0] = 10; <p></p>
      Processador 2: <p></p>
      *A[0][0] = 20;
