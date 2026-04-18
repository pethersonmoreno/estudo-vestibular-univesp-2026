# Matemática: Sequências (Progressões Aritméticas e Geométricas)

As sequências numéricas são listas ordenadas de números que seguem um padrão ou regra. Dentro das sequências, as Progressões Aritméticas (PA) e Progressões Geométricas (PG) são amplamente estudadas e frequentemente cobradas em vestibulares como o da Vunesp.

## 1. Noção de Sequência

Uma **sequência** é um conjunto de números ou elementos dispostos em uma ordem específica. Cada elemento da sequência é chamado de termo e é geralmente denotado por $-n$, onde $n$ indica a posição do termo na sequência.

### Lei de Formação (ou Termo Geral)
É a fórmula que permite calcular qualquer termo da sequência diretamente a partir de sua posição $n$.

**Exemplo:** A sequência $-n = 2n + 1$ gera os termos:
*   $a_1 = 2(1) + 1 = 3$
*   $a_2 = 2(2) + 1 = 5$
*   $a_3 = 2(3) + 1 = 7$
Sequência: (3, 5, 7, ...)

### Lei de Recorrência
Define um termo da sequência em função do(s) termo(s) anterior(es). Necessita de um ou mais termos iniciais para ser usada.

**Exemplo:** A sequência $-n = a_{n-1} + 2$, com $a_1 = 3$ gera os termos:
*   $a_1 = 3$
*   $a_2 = a_1 + 2 = 3 + 2 = 5$
*   $a_3 = a_2 + 2 = 5 + 2 = 7$
Sequência: (3, 5, 7, ...)

## 2. Progressão Aritmética (PA)

Uma **Progressão Aritmética (PA)** é uma sequência numérica em que a diferença entre qualquer termo e seu antecessor é constante. Essa diferença constante é chamada de **razão (r)**.

*   **Fórmula do Termo Geral:** $-n = a_1 + (n-1)r$
    *   $-n$: n-ésimo termo
    *   $a_1$: primeiro termo
    *   $n$: posição do termo
    *   $r$: razão da PA
*   **Soma dos n Primeiros Termos:** $S_n = \frac{(a_1 + -n)n}{2}$

**Exemplo:** PA (2, 5, 8, 11, ...)
*   Razão $r = 5 - 2 = 3$
*   $a_4 = a_1 + (4-1)r = 2 + 3(3) = 2 + 9 = 11$

## 3. Progressão Geométrica (PG)

Uma **Progressão Geométrica (PG)** é uma sequência numérica em que o quociente entre qualquer termo e seu antecessor é constante. Essa razão constante é chamada de **razão (q)**.

*   **Fórmula do Termo Geral:** $-n = a_1 \cdot q^{n-1}$
    *   $-n$: n-ésimo termo
    *   $a_1$: primeiro termo
    *   $n$: posição do termo
    *   $q$: razão da PG
*   **Soma dos n Primeiros Termos:** $S_n = \frac{a_1(q^n - 1)}{q - 1}$ (para $q \neq 1$)
*   **Soma dos Termos de uma PG Infinita:** $S_{\infty} = \frac{a_1}{1 - q}$ (para $|q| < 1$)

**Exemplo:** PG (3, 6, 12, 24, ...)
*   Razão $q = 6 / 3 = 2$
*   $a_4 = a_1 \cdot q^{4-1} = 3 \cdot 2^3 = 3 \cdot 8 = 24$

## Exercícios Estilo Vunesp

**Exercício 1 (VUNESP - Adaptado)**

Considere uma Progressão Aritmética (PA) em que o primeiro termo é 5 e a razão é 3. O 10º termo dessa PA é:

A) 29
B) 32
C) 35
D) 38
E) 41

**Resolução:**
*   $a_1 = 5$
*   $r = 3$
*   $n = 10$
*   Usando a fórmula do termo geral da PA: $-n = a_1 + (n-1)r$
*   $a_{10} = 5 + (10-1)3$
*   $a_{10} = 5 + 9 \times 3$
*   $a_{10} = 5 + 27$
*   $a_{10} = 32$

**Resposta:** B

---

**Exercício 2 (VUNESP - Adaptado)**

Em uma Progressão Geométrica (PG), o primeiro termo é 2 e a razão é 3. A soma dos 4 primeiros termos dessa PG é:

A) 20
B) 40
C) 80
D) 100
E) 120

**Resolução:**
*   $a_1 = 2$
*   $q = 3$
*   $n = 4$
*   Usando a fórmula da soma dos n primeiros termos da PG: $S_n = \frac{a_1(q^n - 1)}{q - 1}$
*   $S_4 = \frac{2(3^4 - 1)}{3 - 1}$
*   $S_4 = \frac{2(81 - 1)}{2}$
*   $S_4 = 80$

**Resposta:** C
