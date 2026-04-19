# Matemática: Funções: Função Quadrática

## Função Quadrática na Vunesp

A Vunesp frequentemente aborda funções quadráticas em problemas que envolvem áreas, maximização/minimização de lucros ou custos, trajetória de objetos (parábolas) e gráficos. É fundamental compreender a estrutura da função, a forma da parábola, o cálculo de raízes, vértice e a interpretação desses elementos em diferentes contextos.

---

## 1. Definição de Função Quadrática (Função do 2º Grau)

Uma função quadrática é definida pela lei $f(x) = ax^2 + bx + c$, onde $a, b, c$ são números reais e $a \neq 0$.

-   **Gráfico:** O gráfico de uma função quadrática é uma **parábola**.

### 1.1. Coeficientes:

-   **$a$ (coeficiente do $x^2$):**
    -   Determina a concavidade da parábola.
    -   Se $a > 0$, a concavidade é para **cima** ($\cup$). O vértice será um ponto de **mínimo**.
    -   Se $a < 0$, a concavidade é para **baixo** ($\cap$). O vértice será um ponto de **máximo**.
-   **$b$ (coeficiente do $x$):** Influencia a posição do vértice e das raízes.
-   **$c$ (coeficiente constante):** É o ponto onde a parábola intercepta o eixo $y$ (quando $x=0$, $f(0) = c$).

## 2. Raízes da Função Quadrática

As raízes (ou zeros) da função são os valores de $x$ para os quais $f(x) = 0$. Encontram-se resolvendo a equação $ax^2 + bx + c = 0$ usando a **Fórmula de Bhaskara**:

$x = \frac{-b \pm \sqrt{\Delta}}{2a}$

Onde $\Delta = b^2 - 4ac$ (discriminante).

-   Se $\Delta > 0$: Duas raízes reais e distintas (a parábola intercepta o eixo $x$ em dois pontos).
-   Se $\Delta = 0$: Uma raiz real (ou duas raízes reais e iguais) (a parábola tangencia o eixo $x$ em um ponto).
-   Se $\Delta < 0$: Nenhuma raiz real (a parábola não intercepta o eixo $x$).

## 3. Vértice da Parábola

O vértice ($V$) é o ponto de máximo ou de mínimo da função quadrática.

-   **Coordenada $x$ do vértice ($x_v$):** $x_v = \frac{-b}{2a}$
-   **Coordenada $y$ do vértice ($y_v$):** $y_v = \frac{-\Delta}{4a}$ ou $y_v = f(x_v)$

## 4. Eixo de Simetria

É uma linha vertical que passa pelo vértice da parábola, dividindo-a em duas partes simétricas. A equação do eixo de simetria é $x = x_v$.

---

## 📝 Exercícios Estilo Vunesp

### Exercício 1 (Raízes da Função Quadrática)

As raízes da função $f(x) = x^2 - 5x + 6$ são:

a) 1 e 6

b) -1 e -6

c) 2 e 3

d) -2 e -3

e) 0 e 5

**Resposta Correta:** c)

**Resolução (Fórmula de Bhaskara):**
$a=1, b=-5, c=6$

1.  **Calcular $\Delta$:**
    $\Delta = b^2 - 4ac = (-5)^2 - 4(1)(6) = 25 - 24 = 1$

2.  **Calcular $x$:**
    $x = \frac{-(-5) \pm \sqrt{1}}{2(1)} = \frac{5 \pm 1}{2}$

    $x_1 = \frac{5 + 1}{2} = \frac{6}{2} = 3$
    $x_2 = \frac{5 - 1}{2} = \frac{4}{2} = 2$

As raízes são 2 e 3.

### Exercício 2 (Vértice da Parábola)

A função quadrática $f(x) = -x^2 + 4x - 3$ representa o lucro de uma empresa, onde $x$ é a quantidade de produtos vendidos. O valor máximo de lucro que essa empresa pode obter é:

a) R$ 1,00

b) R$ 2,00

c) R$ 3,00

d) R$ 4,00

e) R$ 5,00

**Resposta Correta:** a)

**Resolução (Coordenada $y$ do vértice):**
$a=-1, b=4, c=-3$

1.  **Calcular $\Delta$:**
    $\Delta = b^2 - 4ac = (4)^2 - 4(-1)(-3) = 16 - 12 = 4$

2.  **Calcular $y_v$ (valor máximo, pois $a < 0$):**
    $y_v = \frac{-\Delta}{4a} = \frac{-4}{4(-1)} = \frac{-4}{-4} = 1$

O valor máximo de lucro é R$ 1,00.
