# **Atividade U1S1 - Pós-aula**

>### Escolha um exercício de uma prova de computação do ENADE que esteja relacionado ao assunto desta unidade de ensino e seção (U1S1), resolva à mão no caderno, e apresente na próxima aula. Endereço do website do Exame Nacional de Desempenho dos Estudantes (ENADE), contendo a provas no formato PDF para serem baixadas:
https://www.gov.br/inep/pt-br/areas-de-atuacao/avaliacao-e-exames-educacionais/enade/

Questão escolinha
### QUESTÃO 16 

Na programação de sistemas embarcados, algumas posições de memória servem para diferentes propósitos, não apenas para armazenar valores. Em algumas dessas memórias, cada um dos bits possui um significado diferente, 
sendo necessário manipulá-los individualmente ou em pequenos grupos.  Por isso, o conhecimento da álgebra booliana, bem como dos operadores utilizados para realizar operações binárias nas linguagens de programação, é essencial para o 
desenvolvimento desse tipo de sistema. ALMEIDA, R. M.; MORAES, C. H. V.; SERAPHIM, T. F. P. Programação de Sistemas Embarcados: desenvolvendo  software para microcontroladores em linguagem C. Rio de Janeiro: Elsevier, 2016 (adaptado). 

A partir dessas informações, observe o código apresentado a seguir, escrito na linguagem C, que faz uso de operações binárias sobre variáveis inteiras.
Como exemplo, em 2023 existe a prova de Engenharia da Computação, em 2021 existe a prova de Ciência da Computação, e assim por diante. Leia com atenção todas as provas relacionadas ao curso.

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
}

fff