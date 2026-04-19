# Matemática: Funções: Gráfico de Funções Expressas por Sentenças

## Gráficos de Funções na Vunesp

A Vunesp frequentemente explora a interpretação e a construção de gráficos de funções, incluindo aquelas definidas por múltiplas sentenças (funções por partes). As questões podem exigir a identificação de pontos específicos, intervalos de crescimento/decrescimento, o domínio e a imagem, ou a relação entre o gráfico e uma situação-problema.

---

## 1. Gráfico de Funções por uma Sentença

Um gráfico é a representação visual da relação entre a variável independente ($x$) e a variável dependente ($y = f(x)$) em um plano cartesiano.

-   **Eixo x (abscissas):** Representa os valores de entrada da função (domínio).
-   **Eixo y (ordenadas):** Representa os valores de saída da função (imagem).

### Tipos Comuns de Funções e Seus Gráficos:

-   **Função Afim (1º grau):** $f(x) = ax + b$
    -   Gráfico: Uma linha reta.
    -   `a` (coeficiente angular): Inclinação da reta. Se $a > 0$, crescente; se $a < 0$, decrescente; se $a = 0$, constante.
    -   `b` (coeficiente linear): Ponto onde a reta intercepta o eixo y.

-   **Função Quadrática (2º grau):** $f(x) = ax^2 + bx + c$
    -   Gráfico: Uma parábola.
    -   `a`: Se $a > 0$, concavidade para cima; se $a < 0$, concavidade para baixo.
    -   Vértice: Ponto de máximo ou mínimo da parábola.
    -   Raízes: Pontos onde a parábola intercepta o eixo x ($f(x) = 0$).

-   **Função Exponencial:** $f(x) = a^x$, com $a > 0$ e $a \neq 1$.
    -   Gráfico: Curva que cresce ou decresce rapidamente.
    -   Se $a > 1$, crescente; se $0 < a < 1$, decrescente.

## 2. Gráfico de Funções por Diversas Sentenças (Funções Definidas por Partes)

São funções cuja regra de formação muda dependendo do intervalo do domínio.

### Características:

-   Cada "pedaço" da função tem sua própria lei de formação e um domínio específico.
-   O gráfico é formado pela união dos gráficos de cada sentença nos seus respectivos intervalos.
-   Atenção aos pontos de transição: verificar se a função é contínua (o gráfico não tem "saltos") ou descontínua nesses pontos.
    -   Usa-se bolinha `fechada` ($\bullet$) para pontos que pertencem ao intervalo.
    -   Usa-se bolinha `aberta` ($\circ$) para pontos que não pertencem ao intervalo.

**Exemplo:**
$f(x) = \begin{cases}
x + 1, & \text{se } x < 0 \\
x^2, & \text{se } x \ge 0
\end{cases}$

Neste exemplo, para $x < 0$, a função é uma reta ($y = x+1$). Para $x \ge 0$, a função é uma parábola ($y = x^2$).

No ponto $x=0$, o gráfico muda de comportamento.

---

## 📝 Exercícios Estilo Vunesp

### Exercício 1 (Gráfico de Função Afim)

O gráfico de uma função $f(x) = -2x + 4$ intercepta o eixo $x$ e o eixo $y$ nos pontos, respectivamente:

a) $(0, 4)$ e $(2, 0)$

b) $(4, 0)$ e $(0, 2)$

c) $(0, 2)$ e $(4, 0)$

d) $(2, 0)$ e $(0, 4)$

e) $(0, 0)$ e $(2, 4)$

**Resposta Correta:** d)

**Resolução:**
1.  **Intercepto com o eixo $y$ (onde $x=0$):**

    $f(0) = -2(0) + 4 = 4$
    
    Então, o ponto é $(0, 4)$.

2.  **Intercepto com o eixo $x$ (onde $f(x)=0$):**

    $0 = -2x + 4 \implies 2x = 4 \implies x = 2$
    
    Então, o ponto é $(2, 0)$.

Portanto, intercepta o eixo $x$ em $(2, 0)$ e o eixo $y$ em $(0, 4)$.

### Exercício 2 (Interpretação de Gráfico por Partes)

Considere o gráfico de uma função $g(x)$ definida por partes:

```
   y
   ^
   |  .
   |  . .
   |  .   .
   |  .     .
   +-----------> x
   0

(Imagine um gráfico que é uma linha reta decrescente de x=-2, y=4 até x=0, y=2 (segmento 1), e depois uma linha reta crescente de x=0, y=2 até x=2, y=4 (segmento 2).)
```

(Considerando que o gráfico parte de $(-2, 4)$ em linha reta até $(0, 2)$, e depois de $(0, 2)$ em linha reta até $(2, 4)$.)

Assinale a alternativa correta sobre a função $g(x)$:

a) A função é constante no intervalo $[-2, 2]$.

b) O ponto $(0, 2)$ não pertence ao domínio da função.

c) No intervalo $(0, 2]$, a função é crescente.

d) O valor mínimo da função é 4.

e) A função é decrescente em todo o seu domínio.

**Resposta Correta:** c)

- No intervalo $(0, 2]$, a linha do gráfico está subindo, indicando que a função é crescente.

**Explicação das Incorretas:**

- a) A função não é constante; ela decresce e depois cresce.

- b) O ponto $(0, 2)$ pertence ao domínio e à imagem da função, sendo o ponto de transição.

- d) O valor mínimo da função é 2, atingido em $x=0$.

- e) A função é decrescente no intervalo $[-2, 0]$ e crescente no intervalo $[0, 2]$.
