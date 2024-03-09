# **Atividade U1S1 - Pós-aula**

### Dada uma sequência de caracteres * *  S = s1, s2, ..., sn, uma subsequência de S é dada pela remoção de zero ou mais caracteres de S. Formalmente, a sequência X = x1, x2, ..., xk é subsequência de S se existe uma sequência crescente de índices i1, ..., ik de S, tal que xj = Sij para todo j = 1, 2, ..., k. Define-se, também, um prefixo da sequência S com comprimento i para i = 0, ..., n, como Si = s1, s2, ..., si . 

## Questão

### QUESTÃO 16 


Na programação de sistemas embarcados, algumas posições de memória servem para diferentes propósitos, não apenas para armazenar valores. Em algumas dessas memórias, cada um dos bits possui um significado diferente, 
sendo necessário manipulá-los individualmente ou em pequenos grupos.  Por isso, o conhecimento da álgebra booliana, bem como dos operadores utilizados para realizar operações binárias nas linguagens de programação, é essencial para o 
desenvolvimento desse tipo de sistema. ALMEIDA, R. M.; MORAES, C. H. V.; SERAPHIM, T. F. P. Programação de Sistemas Embarcados: desenvolvendo  software para microcontroladores em linguagem C. Rio de Janeiro: Elsevier, 2016 (adaptado). 


A partir dessas informações, observe o código apresentado a seguir, escrito na linguagem C, que faz uso de operações binárias sobre variáveis inteiras.
Como exemplo, em 2023 existe a prova de Engenharia da Computação, em 2021 existe a prova de Ciência da Computação, e assim por diante. Leia com atenção todas as provas relacionadas ao curso.

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

## Após a chamada desse programa, caso o usuário entre com os valores 10 e 1, nessa ordem, qual será, exatamente, o valor da saída do programa? 
<p> </p>

- [ ] A. 10 1 0
- [ ] B. 10 1 11
- [ ] C. 11 11 11
- [ ] D. 15 12 2
- [X] E. 15 13 0
