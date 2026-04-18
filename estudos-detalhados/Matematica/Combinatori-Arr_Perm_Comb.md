# Matemática: Análise Combinatória: Arranjos, Permutações e Combinações Simples

## Arranjos, Permutações e Combinações na Vunesp

A Vunesp frequentemente apresenta problemas de análise combinatória que exigem a distinção entre arranjos, permutações e combinações. É crucial entender quando a ordem dos elementos importa (arranjos e permutações) e quando não importa (combinações), e aplicar a fórmula correta para cada situação.

---

## 1. Permutação Simples

Utilizada para calcular o número de maneiras de organizar (ordenar) todos os elementos de um conjunto.

-   **Quando usar:** A ordem importa e todos os elementos são usados.
-   **Fórmula:** $P_n = n!$
    -   Onde $n$ é o número de elementos.
    -   $n!$ (fatorial de $n$) = $n \times (n-1) \times (n-2) \times ... \times 1$. Por definição, $0! = 1$.

**Exemplo:** De quantas maneiras diferentes 3 livros podem ser organizados em uma prateleira?
-   $P_3 = 3! = 3 \times 2 \times 1 = 6$ maneiras.

## 2. Arranjo Simples

Utilizado para calcular o número de maneiras de escolher e ordenar $k$ elementos de um conjunto de $n$ elementos distintos. A ordem dos elementos escolhidos importa.

-   **Quando usar:** A ordem importa e nem todos os elementos são usados.
-   **Fórmula:** $A_{n,k} = \frac{n!}{(n-k)!}$
    -   Onde $n$ é o número total de elementos.
    -   $k$ é o número de elementos a serem escolhidos e ordenados.

**Exemplo:** Quantos números de 2 algarismos distintos podemos formar com os dígitos $\{1, 2, 3\}$?
-   $n=3, k=2$
-   $A_{3,2} = \frac{3!}{(3-2)!} = \frac{3!}{1!} = \frac{6}{1} = 6$ números (12, 13, 21, 23, 31, 32).

## 3. Combinação Simples

Utilizada para calcular o número de maneiras de escolher $k$ elementos de um conjunto de $n$ elementos distintos, sem que a ordem dos elementos escolhidos importe.

-   **Quando usar:** A ordem NÃO importa e nem todos os elementos são usados.
-   **Fórmula:** $C_{n,k} = \binom{n}{k} = \frac{n!}{k!(n-k)!}$

**Exemplo:** De quantas maneiras diferentes podemos escolher 2 pessoas de um grupo de 3 ($\{A, B, C\}$)?
-   $n=3, k=2$
-   $C_{3,2} = \frac{3!}{2!(3-2)!} = \frac{3!}{2!1!} = \frac{6}{2 \times 1} = 3$ maneiras ($\{A,B\}, \{A,C\}, \{B,C\}$).
    -   Note que $\{A,B\}$ é o mesmo que $\{B,A\}$, por isso a ordem não importa.

---

## 📝 Exercícios Estilo Vunesp

### Exercício 1 (Permutação)

De quantas maneiras diferentes as letras da palavra "AMOR" podem ser rearranjadas para formar anagramas?

a) 4
b) 12
c) 24
d) 48
e) 120

**Resposta Correta:** c)

**Resolução:**
A palavra "AMOR" tem 4 letras distintas. Queremos rearranjar todas elas, então é uma permutação de 4 elementos.
$P_4 = 4! = 4 \times 3 \times 2 \times 1 = 24$ maneiras.

### Exercício 2 (Combinação)

Um grupo de 8 pessoas precisa formar uma comissão de 3 membros. De quantas maneiras diferentes essa comissão pode ser formada?

a) 6
b) 24
c) 56
d) 336
e) 40320

**Resposta Correta:** c)

**Resolução:**
De um grupo de 8 pessoas ($n=8$), queremos escolher 3 ($k=3$). A ordem das pessoas na comissão não importa (Comissão A-B-C é a mesma que B-A-C). Portanto, é uma combinação.

$C_{8,3} = \frac{8!}{3!(8-3)!} = \frac{8!}{3!5!} = \frac{8 \times 7 \times 6 \times 5!}{3 \times 2 \times 1 \times 5!} = \frac{8 \times 7 \times 6}{6} = 8 \times 7 = 56$

A comissão pode ser formada de 56 maneiras diferentes.
