# Funções: Taxa de Variação (Crescimento Linear, Quadrático, Exponencial)

Compreender a taxa de variação de uma função é fundamental para analisar como uma grandeza muda em relação a outra. Estudaremos a taxa de variação em três tipos principais de crescimento: linear, quadrático e exponencial.

## Taxa de Variação Média

A **taxa de variação média** de uma função $f(x)$ em um intervalo $[x_1, x_2]$ é dada pela razão entre a variação dos valores de y ($\Delta y$) e a variação dos valores de x ($\Delta x$).

Fórmula: $$TVM = \frac{\Delta y}{\Delta x} = \frac{f(x_2) - f(x_1)}{x_2 - x_1}$$

Geometricamente, a TVM representa a inclinação da reta secante que conecta os pontos $(x_1, f(x_1))$ e $(x_2, f(x_2))$ no gráfico da função.

## Tipos de Crescimento e Suas Taxas de Variação

### 1. Crescimento Linear (Função do 1º Grau)
*   **Função:** $f(x) = ax + b$, onde $a \neq 0$.
*   **Característica:** A taxa de variação é **constante**. Para cada unidade de aumento em x, f(x) aumenta (ou diminui) por um valor fixo $a$.
*   **Gráfico:** Uma linha reta.
*   **Taxa de Variação:** A própria constante $a$ (coeficiente angular).

**Exemplo:** O salário de um vendedor é R$ 1.000,00 fixos mais R$ 50,00 por venda. $S(v) = 1000 + 50v$. A taxa de variação é 50 R$/venda.

### 2. Crescimento Quadrático (Função do 2º Grau)
*   **Função:** $f(x) = ax^2 + bx + c$, onde $a \neq 0$.
*   **Característica:** A taxa de variação **não é constante**, mas sim **linearmente crescente ou decrescente**. A variação da variação é constante (segunda diferença constante).
*   **Gráfico:** Uma parábola.
*   **Taxa de Variação:** Aumenta ou diminui de forma constante (a reta secante fica cada vez mais inclinada ou menos inclinada).

**Exemplo:** A área de um quadrado em função do seu lado $A(l) = l^2$. A taxa de variação da área não é constante; aumentar o lado de 1 para 2 aumenta a área em 3, mas de 2 para 3 aumenta em 5.

### 3. Crescimento Exponencial (Função Exponencial)
*   **Função:** $f(x) = k \cdot a^x$, onde $a > 0, a \neq 1, k \neq 0$.
*   **Característica:** A taxa de variação **não é constante** e cresce (ou decresce) em **progressão geométrica**. A variação percentual é constante. Para cada unidade de aumento em x, f(x) é multiplicado por um fator constante $a$.
*   **Gráfico:** Uma curva que cresce ou decresce muito rapidamente.
*   **Taxa de Variação:** Aumenta (ou diminui) cada vez mais rapidamente.

**Exemplo:** O crescimento de uma população de bactérias que dobra a cada hora. $P(t) = P_0 \cdot 2^t$. A taxa de variação do crescimento aumenta dramaticamente com o tempo.

## Comparação das Taxas de Variação

*   **Linear:** Variação constante.
*   **Quadrático:** Variação que aumenta/diminui linearmente.
*   **Exponencial:** Variação que aumenta/diminui exponencialmente (muito mais rápido que o linear ou quadrático para grandes valores de x).

## Exercícios Estilo Vunesp

**Exercício 1 (VUNESP - Adaptado)**

Uma loja vende sanduíches por R$ 12,00 cada, e o custo fixo diário da loja é de R$ 100,00. O lucro diário (L) em função do número de sanduíches vendidos (n) é dado por $L(n) = 12n - 100$. Qual a taxa de variação do lucro em relação ao número de sanduíches vendidos?

A) R$ 100,00/sanduíche
B) R$ 12,00/sanduíche
C) R$ -100,00/sanduíche
D) R$ 88,00/sanduíche
E) R$ 112,00/sanduíche

**Resolução:**
*   A função $L(n) = 12n - 100$ é uma função linear do tipo $y = ax + b$.
*   A taxa de variação é o coeficiente angular $a$.
*   Neste caso, a taxa de variação é R$ 12,00 por sanduíche, que representa o preço de venda de cada sanduíche.

**Resposta:** B

---

**Exercício 2 (VUNESP - Adaptado)**

Considere o crescimento de uma cultura de bactérias modelado pela função $P(t) = 50 \cdot 2^t$, onde P(t) é o número de bactérias após t horas. Assinale a alternativa correta sobre a taxa de variação dessa população:

A) A taxa de variação é constante, aumentando em 50 bactérias por hora.
B) A taxa de variação é linear, aumentando em 100 bactérias por hora.
C) A taxa de variação é constante, dobrando a cada hora.
D) A taxa de variação é exponencial, aumentando cada vez mais rapidamente.
E) A taxa de variação é nula, indicando que a população não cresce.

**Resolução:**
*   A função $P(t) = 50 \cdot 2^t$ é uma função exponencial.
*   Em funções exponenciais, a taxa de variação não é constante; ela cresce (ou decresce) cada vez mais rapidamente, em uma progressão geométrica. Neste caso, a população dobra a cada hora, o que implica um aumento cada vez maior em números absolutos.

**Resposta:** D
