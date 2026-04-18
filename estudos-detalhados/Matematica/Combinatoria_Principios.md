# Matemática: Análise Combinatória: Princípios Multiplicativo e Aditivo

## Análise Combinatória na Vunesp

A Vunesp costuma apresentar problemas de Análise Combinatória que exigem a aplicação dos princípios multiplicativo e aditivo, muitas vezes em situações cotidianas que envolvem arranjos, permutações e combinações. É fundamental identificar qual princípio usar e como montar a estrutura de contagem de forma lógica.

---

## 1. Princípio Multiplicativo (Princípio Fundamental da Contagem - PFC)

Utilizado quando uma decisão é tomada em **etapas sucessivas e independentes**. Se um evento é composto por $n$ etapas, e a primeira etapa pode ocorrer de $p_1$ maneiras, a segunda de $p_2$ maneiras, e assim por diante até a $n$-ésima etapa de $p_n$ maneiras, então o número total de maneiras de o evento ocorrer é o **produto** das possibilidades de cada etapa.

### Quando usar:

-   Quando há opções para cada "casa" ou "posição" a ser preenchida.
-   A ordem importa (implícita ou explicitamente).

### Exemplo:

Uma pessoa tem 3 camisetas e 2 calças. De quantas maneiras diferentes ela pode se vestir?
-   Etapa 1 (escolher camiseta): 3 opções
-   Etapa 2 (escolher calça): 2 opções
-   Total: $3 \times 2 = 6$ maneiras.

## 2. Princípio Aditivo

Utilizado quando um evento pode ocorrer de **duas ou mais maneiras distintas ou mutuamente exclusivas** (uma não acontece se a outra acontece). Se um evento pode ser realizado de $n_1$ maneiras OU de $n_2$ maneiras, e essas maneiras não possuem elementos em comum, então o número total de maneiras de o evento ocorrer é a **soma** das possibilidades.

### Quando usar:

-   Quando há "ou" entre as opções (escolher uma coisa OU outra, mas não as duas ao mesmo tempo).
-   Os conjuntos de resultados são disjuntos (não há sobreposição).

### Exemplo:

Para viajar, uma pessoa pode escolher ir de carro (2 opções de carro) OU de ônibus (3 opções de ônibus). De quantas maneiras diferentes ela pode viajar?
-   Opções de carro: 2
-   Opções de ônibus: 3
-   Total: $2 + 3 = 5$ maneiras.

**Observação:** Se os conjuntos não são disjuntos (há interseção), é preciso usar o Princípio da Inclusão-Exclusão: $N(A \cup B) = N(A) + N(B) - N(A \cap B)$.

---

## 📝 Exercícios Estilo Vunesp

### Exercício 1 (Princípio Multiplicativo)

Uma senha de banco deve ser formada por 4 dígitos. Quantas senhas diferentes podem ser criadas se:

I. Os dígitos podem se repetir.
II. Os dígitos não podem se repetir.

a) I. 1000; II. 990.
b) I. 10000; II. 5040.
c) I. 40; II. 24.
d) I. 10000; II. 1000.
e) I. 5040; II. 10000.

**Resposta Correta:** b)

**Resolução:**
Os dígitos disponíveis são de 0 a 9, totalizando 10 opções.

-   **I. Os dígitos podem se repetir:**
    -   1º dígito: 10 opções
    -   2º dígito: 10 opções
    -   3º dígito: 10 opções
    -   4º dígito: 10 opções
    -   Total: $10 \times 10 \times 10 \times 10 = 10^4 = 10000$ senhas.

-   **II. Os dígitos não podem se repetir:**
    -   1º dígito: 10 opções
    -   2º dígito: 9 opções (um já foi usado)
    -   3º dígito: 8 opções (dois já foram usados)
    -   4º dígito: 7 opções (três já foram usados)
    -   Total: $10 \times 9 \times 8 \times 7 = 5040$ senhas.

### Exercício 2 (Princípio Aditivo)

Uma lanchonete oferece 3 tipos de suco de frutas, 2 tipos de refrigerante e 1 tipo de água. Se um cliente pode pedir apenas uma bebida, quantas opções de bebidas ele tem?

a) 3
b) 2
c) 6
d) 1
e) 7

**Resposta Correta:** c)

**Resolução:**
O cliente escolhe uma bebida. As categorias (suco, refrigerante, água) são mutuamente exclusivas.
-   Opções de suco: 3
-   Opções de refrigerante: 2
-   Opções de água: 1
-   Total (Princípio Aditivo): $3 + 2 + 1 = 6$ opções.
