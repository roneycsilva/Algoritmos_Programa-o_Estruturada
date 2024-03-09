# **Atividade U1S3 - Pós-aula**

<div style="text-align: justify; font-size: 18px; margin: 10px;">
<p> Escolha um exercício de uma prova de computação do ENADE que esteja relacionado ao assunto desta unidade de ensino e seção (U1S1), resolva à mão no caderno, e apresente na próxima aula. Endereço do website do Exame Nacional de Desempenho dos Estudantes (ENADE), contendo a provas no formato PDF para serem baixadas: 
    <p>https://www.gov.br/inep/pt-br/areas-de-atuacao/avaliacao-e-exames-educacionais/enade/</p></p>
</div>

<p style="text-align: justify; font-size: 15px; margin: 10px;">
   Questão
</p>

### QUESTÃO 22 

<div style="text-align: justify; font-size: 18px; margin: 10px;">
<p> Considere um banco de dados relacional formado por três tabelas, conforme é apresentado na figura a seguir. As chaves primárias das tabelas <em>cliente</em> e <em>funcionario</em> são chaves estrangeiras da tabela <em>pessoa</em>.</div>

<p align="center">
  <img width="520" height="300" alt="image_01" src="https://github.com/roneycsilva/Algoritmos_Programa-o_Estruturada/assets/61150519/b6922dc5-48ce-4008-b9b4-fca43a1259b2">
</p>

<div style="text-align: justify; font-size: 18px; margin: 10px;">
<p> A partir dessas informações, considere que se queira realizar uma consulta que liste o nome e o saldo devedor de um subconjunto dos clientes. Essa consulta tem por objetivo encontrar clientes que são funcionários e que possuem saldo devedor maior do que seu salário. Com base nessas informações, assinale a opção que apresenta corretamente a consulta SQL,  em ordem crescente por saldo devedor.</div>

- [ ] A. SELECT * FROM cliente as c INNER JOIN pessoa as p, funcionario as f WHERE c.saldo_devedor > f.salario AND c.id_cliente=p.id_pessoa AND f.id_funcionario=p.id_pessoa ORDER BY c.saldo_devedor ASC 
- [ ] B. SELECT p.nome, c.saldo_devedor FROM cliente as c, pessoa as p WHERE c.saldo_devedor > f.salario AND c.id_cliente=p.id_pessoa AND  f.id_funcionario=p.id_pessoa ORDER BY c.saldo_devedor DESC 
- [ ] C. SELECT p.nome, c.saldo_devedor FROM cliente as c, pessoa as p, funcionario as f WHERE c.saldo_devedor < f.salario AND  c.id_cliente=p.id_pessoa AND f.id_funcionario=p.id_pessoa ORDER BY c.saldo_devedor ASC
- [ ] D. SELECT p.nome, c.saldo_devedor FROM cliente as c LEFT OUTER JOIN pessoa as p on c.id_cliente=p.id_pessoa LEFT OUTER JOIN funcionario as f on p.id_pessoa=f.id_funcionario WHERE c.saldo_devedor > f.salario ORDER BY f.salario, c.saldo_devedor ASC 
- [X] E. SELECT p.nome, c.saldo_devedor FROM cliente as c RIGHT OUTER JOIN pessoa as p ON c.id_cliente=p.id_pessoa RIGHT OUTER JOIN funcionario as f on p.id_pessoa=f.id_funcionario WHERE c.saldo_devedor > f.salario ORDER BY c.saldo_devedor ASC
