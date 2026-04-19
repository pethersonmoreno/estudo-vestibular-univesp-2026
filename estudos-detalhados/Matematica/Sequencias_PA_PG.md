# Sequências: Progressões Aritméticas e Geométricas <span class="tag-media-frequencia">[⚠️ FREQUÊNCIA MÉDIA]</span>

Sequências são conjuntos de elementos (números, figuras, etc.) que seguem uma ordem específica, determinada por uma regra ou lei de formação. As progressões aritméticas (PA) e geométricas (PG) são tipos especiais de sequências numéricas.

## 1.4. Sequências: Noção de Sequência

Uma **sequência** é uma lista ordenada de elementos. Cada elemento é chamado de termo e é geralmente denotado por $-n$, onde $n$ é a posição do termo na sequência (ex: $a_1$ é o primeiro termo, $a_2$ o segundo, e assim por diante).

**Lei de Formação (ou Termo Geral)**: Uma fórmula que permite calcular qualquer termo da sequência diretamente a partir de sua posição $n$.
*Exemplo*: A sequência $(2, 4, 6, 8, ...)$ tem lei de formação $-n = 2n$.

**Lei de Recorrência**: Uma fórmula que define um termo da sequência em função de termos anteriores. Necessita de um ou mais termos iniciais para ser aplicada.
*Exemplo*: A sequência de Fibonacci $(1, 1, 2, 3, 5, ...)$ tem lei de recorrência $-n = a_{n-1} + a_{n-2}$, com $a_1 = 1$ e $a_2 = 1$.

## Progressões Aritméticas (PA)

Uma **Progressão Aritmética (PA)** é uma sequência numérica em que cada termo, a partir do segundo, é obtido somando-se uma constante, chamada **razão (r)**, ao termo anterior.

-   **Fórmula do Termo Geral**: $-n = a_1 + (n-1)r$
    Onde:
    -   $-n$ é o n-ésimo termo
    -   $a_1$ é o primeiro termo
    -   $n$ é a posição do termo
    -   $r$ é a razão da PA

-   **Soma dos Termos de uma PA**: $S_n = \frac{(a_1 + -n)n}{2}$
    Onde:
    -   $S_n$ é a soma dos $n$ primeiros termos

*Exemplo*: PA $(2, 5, 8, 11, ...)$
$a_1 = 2$, $r = 3$.
O 5º termo ($a_5$) seria $a_5 = 2 + (5-1)3 = 2 + 4 \times 3 = 2 + 12 = 14$.

## Progressões Geométricas (PG)

Uma **Progressão Geométrica (PG)** é uma sequência numérica em que cada termo, a partir do segundo, é obtido multiplicando-se o termo anterior por uma constante, chamada **razão (q)**.

-   **Fórmula do Termo Geral**: $-n = a_1 \cdot q^{n-1}$
    Onde:
    -   $-n$ é o n-ésimo termo
    -   $a_1$ é o primeiro termo
    -   $n$ é a posição do termo
    -   $q$ é a razão da PG

-   **Soma dos Termos de uma PG Finita**: $S_n = \frac{a_1(q^n - 1)}{q - 1}$, para $q \ne 1$.

-   **Soma dos Termos de uma PG Infinita**: $S_{\infty} = \frac{a_1}{1 - q}$, para $|q| < 1$.

*Exemplo*: PG $(3, 6, 12, 24, ...)$
$a_1 = 3$, $q = 2$.
O 4º termo ($a_4$) seria $a_4 = 3 \cdot 2^{4-1} = 3 \cdot 2^3 = 3 \cdot 8 = 24$.

---

## Exercícios Estilo Vunesp

**Questão 1 (Vunesp Adaptada):**
Considere uma Progressão Aritmética (PA) cujo primeiro termo é 5 e a razão é 3. Qual o valor do 10º termo desta PA?

a) 27

b) 32

c) 35

d) 40

e) 45

**Resolução:**
Utilizamos a fórmula do termo geral da PA: $-n = a_1 + (n-1)r$.
Dados: $a_1 = 5$, $r = 3$, $n = 10$.
$a_{10} = 5 + (10 - 1) \times 3$
$a_{10} = 5 + 9 \times 3$
$a_{10} = 5 + 27$
$a_{10} = 32$

**Alternativa Correta: b)**

---

**Questão 2 (Vunesp Adaptada):**
Uma Progressão Geométrica (PG) tem como primeiro termo 2 e razão 4. Qual o valor do 4º termo desta PG?

a) 16

b) 32

c) 64

d) 128

e) 256

**Resolução:**
Utilizamos a fórmula do termo geral da PG: $-n = a_1 \cdot q^{n-1}$.
Dados: $a_1 = 2$, $q = 4$, $n = 4$.
$a_4 = 2 \cdot 4^{4-1}$
$a_4 = 2 \cdot 4^3$
$a_4 = 2 \cdot 64$
$a_4 = 128$

**Alternativa Correta: d)**

---

**Exercício 3 (VUNESP - Adaptado)**

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
