# Sistemas Lineares [⚠️ FREQUÊNCIA MÉDIA]

Sistemas lineares são conjuntos de duas ou mais equações lineares que compartilham as mesmas variáveis. A resolução de um sistema linear consiste em encontrar os valores das variáveis que satisfazem simultaneamente todas as equações do sistema.

## 4.1. Resolução e Discussão de um Sistema Linear

### Métodos de Resolução

Existem diversos métodos para resolver sistemas lineares. Os mais comuns são:

1.  **Método da Substituição**:
    -   Isola-se uma das variáveis em uma das equações.
    -   Substitui-se essa expressão nas outras equações.
    -   Resolve-se a nova equação (ou sistema reduzido).
    -   Substitui-se o valor encontrado para encontrar as outras variáveis.
    
    *Exemplo:*
    $\begin{cases}
x + y = 5 \quad (I)
x - y = 1 \quad (II)
\end{cases}$
    De (I), $x = 5 - y$.
    Substituindo em (II): $(5 - y) - y = 1 \Rightarrow 5 - 2y = 1 \Rightarrow -2y = -4 \Rightarrow y = 2$.
    Substituindo $y = 2$ em $x = 5 - y$: $x = 5 - 2 \Rightarrow x = 3$.
    Solução: $(3, 2)$.

2.  **Método da Adição**:
    -   Multiplica-se uma ou ambas as equações por números adequados para que os coeficientes de uma das variáveis sejam opostos.
    -   Soma-se as equações para eliminar essa variável.
    -   Resolve-se a equação resultante.
    -   Substitui-se o valor encontrado em uma das equações originais para encontrar a outra variável.
    
    *Exemplo:*
    $\begin{cases}
x + y = 5 \quad (I)
x - y = 1 \quad (II)
\end{cases}$
    Somando (I) e (II):
    $(x + y) + (x - y) = 5 + 1 \Rightarrow 2x = 6 \Rightarrow x = 3$.
    Substituindo $x = 3$ em (I): $3 + y = 5 \Rightarrow y = 2$.
    Solução: $(3, 2)$.

### Discussão de um Sistema Linear

Um sistema linear pode ser classificado quanto ao número de soluções:

-   **Sistema Possível e Determinado (SPD)**: Possui uma única solução. (Exemplo acima)
-   **Sistema Possível e Indeterminado (SPI)**: Possui infinitas soluções. As equações são equivalentes ou uma é múltipla da outra.
    *Exemplo:*
    $\begin{cases}
x + y = 3
2x + 2y = 6
\end{cases}$
    A segunda equação é o dobro da primeira. Qualquer par $(x, y)$ que satisfaz $x + y = 3$ é solução.
-   **Sistema Impossível (SI)**: Não possui solução. As equações são contraditórias.
    *Exemplo:*
    $\begin{cases}
x + y = 3
x + y = 5
\end{cases}$
    Não há como $x+y$ ser simultaneamente 3 e 5.

## 4.2. Representação Algébrica e Gráfica de um Sistema de Equações Lineares

### Representação Algébrica

Um sistema linear pode ser representado na forma de equações ou em forma matricial.

*Forma de Equações:*
$\begin{cases}
a_{11}x_1 + a_{12}x_2 + ... + a_{1n}x_n = b_1
a_{21}x_1 + a_{22}x_2 + ... + a_{2n}x_n = b_2
...
a_{m1}x_1 + a_{m2}x_2 + ... + a_{mn}x_n = b_m
\end{cases}$

Onde $a_{ij}$ são os coeficientes, $x_j$ são as variáveis e $b_i$ são os termos independentes.

### Representação Gráfica (para sistemas 2x2)

Cada equação linear com duas variáveis $(x, y)$ representa uma reta no plano cartesiano.

-   **SPD (Sistema Possível e Determinado)**: As duas retas se **interceptam em um único ponto**. Este ponto é a solução do sistema.
    (Ex: $x+y=5$ e $x-y=1$ se cruzam no ponto $(3,2)$)

-   **SPI (Sistema Possível e Indeterminado)**: As duas retas são **coincidentes** (a mesma reta). Todos os pontos da reta são soluções.
    (Ex: $x+y=3$ e $2x+2y=6$ representam a mesma reta)

-   **SI (Sistema Impossível)**: As duas retas são **paralelas distintas** (nunca se encontram). Não há ponto em comum.
    (Ex: $x+y=3$ e $x+y=5$ representam retas paralelas)

---

## Exercícios Estilo Vunesp

**Questão 1 (Vunesp Adaptada):**
Considere o sistema de equações lineares:
$\begin{cases}
2x + y = 7
3x - 2y = 0
\end{cases}$
Assinale a alternativa que apresenta a solução $(x, y)$ deste sistema.

a) $(2, 3)$
b) $(3, 1)$
c) $(1, 5)$
d) $(0, 0)$
e) $(1, 2)$

**Resolução:**
Pelo método da substituição:
De $2x + y = 7$, isolamos $y$: $y = 7 - 2x$.
Substituímos na segunda equação:
$3x - 2(7 - 2x) = 0$
$3x - 14 + 4x = 0$
$7x = 14$
$x = 2$
Agora, substituímos $x = 2$ em $y = 7 - 2x$:
$y = 7 - 2(2)$
$y = 7 - 4$
$y = 3$
Solução: $(2, 3)$.

**Alternativa Correta: a)**

---

**Questão 2 (Vunesp Adaptada):**
Em um plano cartesiano, duas retas são dadas pelas equações $y = 2x + 1$ e $y = 2x - 3$. Com base nessas equações, pode-se afirmar que o sistema linear formado por elas é:

a) Possível e Determinado, pois as retas se cruzam em um único ponto.
b) Possível e Indeterminado, pois as retas são coincidentes.
c) Impossível, pois as retas são paralelas e distintas.
d) Impossível, pois as retas são perpendiculares.
e) Possível e Determinado, com solução $(0, 1)$.

**Resolução:**
Ambas as equações estão na forma $y = mx + b$, onde $m$ é o coeficiente angular (inclinação da reta) e $b$ é o coeficiente linear (onde a reta cruza o eixo y).
- Para a primeira reta: $m_1 = 2$ e $b_1 = 1$.
- Para a segunda reta: $m_2 = 2$ e $b_2 = -3$.
Como $m_1 = m_2 = 2$, as retas têm a mesma inclinação, ou seja, são paralelas. Como $b_1 \ne b_2$ (os coeficientes lineares são diferentes), as retas são distintas. Retas paralelas distintas nunca se encontram, portanto, o sistema não possui solução.

**Alternativa Correta: c)**
