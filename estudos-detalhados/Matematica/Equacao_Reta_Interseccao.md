# Matemática: Funções: Equação da Reta e Intersecção de Retas

## Equação da Reta na Vunesp

A Vunesp frequentemente cobra conceitos de geometria analítica relacionados à equação da reta, como a determinação de sua forma reduzida, a interpretação dos coeficientes angular e linear, e o cálculo do ponto de intersecção entre duas retas. Essas questões podem envolver a representação de situações-problema do cotidiano em um plano cartesiano.

---

## 1. Equação da Reta

A reta é a representação gráfica de uma função polinomial do 1º grau ($f(x) = ax + b$).

### 1.1. Forma Reduzida

-   É a forma mais comum: $y = mx + b$
    -   $y$: Variável dependente (ordenada).
    -   $x$: Variável independente (abscissa).
    -   $m$: **Coeficiente Angular** (ou declive) da reta. Indica a inclinação da reta em relação ao eixo $x$. É a tangente do ângulo que a reta forma com o eixo $x$.
        -   $m = \frac{\Delta y}{\Delta x} = \frac{y_2 - y_1}{x_2 - x_1}$
        -   Se $m > 0$, reta crescente.
        -   Se $m < 0$, reta decrescente.
        -   Se $m = 0$, reta horizontal (função constante).
    -   $b$: **Coeficiente Linear**. É o valor de $y$ quando $x=0$, ou seja, o ponto onde a reta intercepta o eixo $y$.

### 1.2. Equações Especiais

-   **Retas Horizontais:** $y = k$ (onde $k$ é uma constante). $m=0$.
-   **Retas Verticais:** $x = k$ (onde $k$ é uma constante). Não representam funções do 1º grau e não possuem coeficiente angular definido (infinito).

## 2. Intersecção de Retas

O ponto de intersecção entre duas retas é o ponto $(x, y)$ que satisfaz ambas as equações simultaneamente. Para encontrá-lo, basta resolver o sistema linear formado pelas duas equações das retas.

### Métodos de Resolução de Sistemas:

-   **Substituição:** Isolar uma variável em uma equação e substituir na outra.
-   **Adição:** Multiplicar as equações por números adequados para que, ao somá-las, uma variável seja eliminada.

### Casos Especiais:

-   **Retas Concorrentes:** Possuem um único ponto de intersecção (sistema com uma única solução).
    -   Coeficientes angulares diferentes ($m_1 \neq m_2$).
-   **Retas Paralelas Distintas:** Não possuem ponto de intersecção (sistema sem solução).
    -   Mesmo coeficiente angular, mas coeficientes lineares diferentes ($m_1 = m_2$ e $b_1 \neq b_2$).
-   **Retas Coincidentes:** Possuem infinitos pontos de intersecção (sistema com infinitas soluções).
    -   Mesmo coeficiente angular e mesmo coeficiente linear ($m_1 = m_2$ e $b_1 = b_2$).

---

## 📝 Exercícios Estilo Vunesp

### Exercício 1 (Equação da Reta)

Uma reta passa pelos pontos $A(2, 5)$ e $B(4, 9)$. Qual a equação reduzida dessa reta?

a) $y = 2x + 1$
b) $y = -2x + 9$
c) $y = x + 3$
d) $y = 2x + 5$
e) $y = 4x - 3$

**Resposta Correta:** a)

**Resolução:**
1.  **Calcular o coeficiente angular ($m$):**
    $m = \frac{y_2 - y_1}{x_2 - x_1} = \frac{9 - 5}{4 - 2} = \frac{4}{2} = 2$

2.  **Usar um dos pontos e o `m` na fórmula $y = mx + b$ para encontrar $b$:**
    Usando o ponto $A(2, 5)$:
    $5 = 2(2) + b$
    $5 = 4 + b$
    $b = 1$

3.  **Escrever a equação reduzida:**
    $y = 2x + 1$

### Exercício 2 (Intersecção de Retas)

As retas representadas pelas equações $y = 3x - 2$ e $y = -x + 6$ se interceptam em qual ponto?

a) $(1, 1)$
b) $(2, 4)$
c) $(3, 3)$
d) $(4, 2)$
e) $(0, -2)$

**Resposta Correta:** b)

**Resolução:**
Para encontrar o ponto de intersecção, igualamos as duas equações:
$3x - 2 = -x + 6$
$3x + x = 6 + 2$
$4x = 8$
$x = 2$

Agora, substituímos o valor de $x$ em uma das equações para encontrar $y$:
Usando $y = 3x - 2$:
$y = 3(2) - 2$
$y = 6 - 2$
$y = 4$

O ponto de intersecção é $(2, 4)$.
