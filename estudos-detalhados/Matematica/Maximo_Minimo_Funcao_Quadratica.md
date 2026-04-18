# Matemática: Funções: Pontos de Máximo e Mínimo em Funções Quadráticas

## Máximo e Mínimo na Vunesp

A Vunesp frequentemente apresenta problemas de otimização que envolvem a determinação de pontos de máximo ou mínimo em funções quadráticas. Essas questões são comuns em contextos de economia (lucro máximo, custo mínimo), física (altura máxima de um projétil) e geometria (área máxima). É crucial saber identificar quando um ponto é de máximo ou mínimo e calcular suas coordenadas.

---

## 1. Vértice da Parábola: Ponto de Máximo ou Mínimo

O gráfico de uma função quadrática $f(x) = ax^2 + bx + c$ é uma parábola. O ponto mais alto ou mais baixo da parábola é chamado de **vértice** ($V$).

-   **Concavidade para cima ( $a > 0$ ):** A parábola tem um ponto de **mínimo**. O vértice é o menor valor que a função pode assumir.
    -   Ex: Abrir os braços para cima como um "U".

-   **Concavidade para baixo ( $a < 0$ ):** A parábola tem um ponto de **máximo**. O vértice é o maior valor que a função pode assumir.
    -   Ex: Abrir os braços para baixo como um "n".

### Fórmulas para as Coordenadas do Vértice:

-   **Abscissa do Vértice ($x_v$):** Indica o valor de $x$ onde ocorre o máximo ou mínimo.
    $x_v = \frac{-b}{2a}$

-   **Ordenada do Vértice ($y_v$):** Indica o valor máximo ou mínimo da função.
    $y_v = \frac{-\Delta}{4a}$ ou $y_v = f(x_v)$
    Onde $\Delta = b^2 - 4ac$ (discriminante).

## 2. Interpretação em Problemas

Ao resolver problemas de máximo e mínimo, é importante:

-   **Identificar a função quadrática:** Geralmente, a situação é modelada por $f(x) = ax^2 + bx + c$.
-   **Determinar a concavidade:** O sinal de `a` indicará se buscamos um máximo ou um mínimo.
-   **Calcular $x_v$:** Descobrir qual valor da variável independente (quantidade de produtos, tempo, etc.) leva ao máximo ou mínimo.
-   **Calcular $y_v$:** Encontrar o valor máximo ou mínimo da função (lucro máximo, custo mínimo, altura máxima, etc.).

---

## 📝 Exercícios Estilo Vunesp

### Exercício 1 (Ponto de Máximo)

A trajetória de uma bola chutada por um jogador pode ser descrita pela função $h(t) = -t^2 + 6t$, onde $h(t)$ é a altura da bola em metros e $t$ é o tempo em segundos após o chute. Qual a altura máxima atingida pela bola?

a) 6 metros
b) 9 metros
c) 12 metros
d) 15 metros
e) 18 metros

**Resposta Correta:** b)

**Resolução:**
A função é $h(t) = -t^2 + 6t$. Comparando com $at^2 + bt + c$, temos $a=-1$, $b=6$, $c=0$. Como $a < 0$, a parábola tem concavidade para baixo, e o vértice é um ponto de máximo.

1.  **Calcular $\Delta$:**
    $\Delta = b^2 - 4ac = (6)^2 - 4(-1)(0) = 36 - 0 = 36$

2.  **Calcular $h_v$ (altura máxima, que é o $y_v$):**
    $h_v = \frac{-\Delta}{4a} = \frac{-36}{4(-1)} = \frac{-36}{-4} = 9$

A altura máxima atingida pela bola é de 9 metros.

### Exercício 2 (Ponto de Mínimo)

O custo diário de produção de um certo item é dado pela função $C(x) = x^2 - 10x + 30$, onde $x$ é o número de itens produzidos e $C(x)$ é o custo em reais. Para que o custo de produção seja mínimo, quantos itens devem ser produzidos?

a) 3 itens
b) 4 itens
c) 5 itens
d) 6 itens
e) 7 itens

**Resposta Correta:** c)

**Resolução:**
A função é $C(x) = x^2 - 10x + 30$. Comparando com $ax^2 + bx + c$, temos $a=1$, $b=-10$, $c=30$. Como $a > 0$, a parábola tem concavidade para cima, e o vértice é um ponto de mínimo.

Para que o custo seja mínimo, precisamos encontrar o valor de $x$ (número de itens) que corresponde ao vértice, ou seja, $x_v$.

$x_v = \frac{-b}{2a} = \frac{-(-10)}{2(1)} = \frac{10}{2} = 5$

Devem ser produzidos 5 itens para que o custo de produção seja mínimo.
