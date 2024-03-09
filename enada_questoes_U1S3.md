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

<div style="text-align: justify; font-size: 18px; margin: 10px;">
<p>A partir dessas informações, observe o código apresentado a seguir, escrito na linguagem C, que faz uso de operações binárias sobre variáveis inteiras.
Como exemplo, em 2023 existe a prova de Engenharia da Computação, em 2021 existe a prova de Ciência da Computação, e assim por diante. Leia com atenção todas as provas relacionadas ao curso.
</div>

<p></p>

    //
    #include <stdio.h>

    int main() {
    // Declaração de variáveis
    int a, b;
    int x, y, z;

    // Entrada de dados
    printf("Digite dois números inteiros: ");
    scanf("%d %d", &a, &b);

    // Inicialização de variáveis
    x = a;
    y = b;
    z = a + b;

    // Processamento
    while (a) {
        x = x | b;
        y = y ^ a;
        z = z & (a + b);
        a = a >> 1;
        b = b << 1;
    }

    // Saída de resultados
    printf("Resultados: %d %d %d\n", x, y, z);

    return 0;

<div style="text-align: justify; font-size: 18px; margin: 10px;">
<p> Após a chamada desse programa, caso o usuário entre com os valores 10 e 1, nessa ordem, qual será, exatamente, o valor da saída do programa? 

</div>
<p> </p>

- [ ] A. 10 1 0
- [ ] B. 10 1 11
- [ ] C. 11 11 11
- [ ] D. 15 12 2
- [X] E. 15 13 0
