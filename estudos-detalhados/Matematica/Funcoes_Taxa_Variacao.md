# Matemática: Funções: Taxa de Variação (Crescimento Linear, Quadrático, Exponencial)

## Taxa de Variação na Vunesp

A Vunesp frequentemente apresenta problemas que envolvem a análise de crescimento e decrescimento de grandezas, representados por funções lineares, quadráticas ou exponenciais. As questões podem exigir a interpretação de gráficos, a identificação do tipo de crescimento/decaimento e a aplicação de modelos matemáticos a situações reais.

---

## 1. Taxa de Variação Média

A taxa de variação média de uma função $f(x)$ em um intervalo $[a, b]$ é dada por:

$T_{VM} = \frac{f(b) - f(a)}{b - a}$

Ela representa a inclinação da reta secante ao gráfico da função nos pontos $(a, f(a))$ e $(b, f(b))$.

## 2. Tipos de Crescimento e Decaimento

### 2.1. Crescimento Linear (Função Afim)

-   **Características:** A taxa de variação é constante. O aumento ou diminuição ocorre sempre na mesma proporção em intervalos iguais de tempo.
-   **Fórmula:** $f(x) = ax + b$
    -   `a` é a taxa de variação (coeficiente angular).
    -   Se $a > 0$, crescimento linear.
    -   Se $a < 0$, decaimento linear.
-   **Gráfico:** Uma linha reta.

**Exemplo:** Um carro que percorre 60 km a cada hora (taxa constante de 60 km/h).

### 2.2. Crescimento Quadrático (Função Quadrática)

-   **Características:** A taxa de variação não é constante; ela muda de forma não uniforme. O crescimento (ou decaimento) é cada vez mais rápido (ou lento).
-   **Fórmula:** $f(x) = ax^2 + bx + c$
    -   Se $a > 0$, a concavidade é para cima, e a função cresce mais rapidamente após o vértice (ou decresce até o vértice).
    -   Se $a < 0$, a concavidade é para baixo, e a função decresce mais rapidamente após o vértice (ou cresce até o vértice).
-   **Gráfico:** Uma parábola.

**Exemplo:** A área de um quadrado em função do comprimento de seu lado ($A = L^2$).

### 2.3. Crescimento Exponencial (Função Exponencial)

-   **Características:** A taxa de variação é proporcional ao valor atual da função. O crescimento (ou decaimento) é extremamente rápido (ou lento) e contínuo, duplicando (ou reduzindo pela metade) em intervalos regulares de tempo.
-   **Fórmula:** $f(x) = C \cdot a^x$ ou $f(x) = C \cdot e^{kx}$
    -   $C$ é o valor inicial.
    -   `a` (ou $e^k$) é a base de crescimento. Se $a > 1$, crescimento; se $0 < a < 1$, decaimento.
-   **Gráfico:** Uma curva que cresce ou decresce muito rapidamente.

**Exemplo:** Crescimento populacional sem limites ou juros compostos.

---

## 📝 Exercícios Estilo Vunesp

### Exercício 1 (Identificação de Tipo de Crescimento)

Uma empresa de tecnologia registra que sua base de usuários duplica a cada ano. Qual o tipo de crescimento que melhor descreve essa situação?

a) Linear

b) Quadrático

c) Exponencial

d) Logarítmico

e) Constante

**Resposta Correta:** c)
- Quando uma quantidade duplica (ou multiplica por um fator constante) em intervalos regulares, o crescimento é exponencial.

### Exercício 2 (Taxa de Variação Linear)

Um reservatório de água com capacidade máxima de 1000 litros está sendo esvaziado. Às 8h da manhã, ele continha 800 litros. Às 10h da manhã, o volume de água era de 600 litros. Se o esvaziamento ocorre de forma linear, qual a taxa de esvaziamento por hora?

a) 50 litros/hora

b) 100 litros/hora

c) 150 litros/hora

d) 200 litros/hora

e) 250 litros/hora

**Resposta Correta:** b)

**Resolução:**
-   Noção de função linear: $V(t) = at + b$
-   No intervalo das 8h às 10h (2 horas de diferença):
    -   Mudança no volume ($\Delta V$) = 600 L - 800 L = -200 L
    -   Mudança no tempo ($\Delta t$) = 10h - 8h = 2 horas

-   **Taxa de esvaziamento (taxa de variação):**
    $T_{VM} = \frac{\Delta V}{\Delta t} = \frac{-200 \text{ L}}{2 \text{ h}} = -100 \text{ litros/hora}$

A taxa de esvaziamento é de 100 litros por hora (o sinal negativo indica decaimento).
