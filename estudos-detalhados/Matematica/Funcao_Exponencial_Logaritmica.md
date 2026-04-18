# Função Exponencial e Logarítmica <span class="tag-alta-frequencia">🔥 ALTA FREQUÊNCIA</span>

As funções exponencial e logarítmica são inversas uma da outra e têm vasta aplicação em diversas áreas, como finanças, biologia e física. O domínio desses conceitos é crucial para a resolução de problemas em vestibulares.

## 5.8. Função Exponencial e Função Logarítmica

### Função Exponencial

Uma **função exponencial** é uma função de forma $f(x) = a^x$, onde $a$ é a base (com $a > 0$ e $a \ne 1$) e $x$ é o expoente.

**Características:**
-   **Domínio**: Todos os números reais ($D = \mathbb{R}$).
-   **Imagem**: Todos os números reais positivos ($Im = \mathbb{R}_+$).
-   **Gráfico**:
    -   Se $a > 1$: a função é crescente. Quanto maior $x$, maior $f(x)$.
    -   Se $0 < a < 1$: a função é decrescente. Quanto maior $x$, menor $f(x)$.
-   Sempre passa pelo ponto $(0, 1)$, pois $a^0 = 1$.
-   O eixo $x$ é uma assíntota (a função se aproxima, mas nunca toca o eixo $x$).

*Exemplo*: $f(x) = 2^x$

### Função Logarítmica

A **função logarítmica** é a função inversa da função exponencial. Ela é definida como $f(x) = \log_a x$, onde $a$ é a base (com $a > 0$ e $a \ne 1$) e $x$ é o logaritmando (com $x > 0$).
A expressão $\log_a x = y$ significa que $a^y = x$.

**Características:**
-   **Domínio**: Todos os números reais positivos ($D = \mathbb{R}_+$).
-   **Imagem**: Todos os números reais ($Im = \mathbb{R}$).
-   **Gráfico**:
    -   Se $a > 1$: a função é crescente.
    -   Se $0 < a < 1$: a função é decrescente.
-   Sempre passa pelo ponto $(1, 0)$, pois $\log_a 1 = 0$.
-   O eixo $y$ é uma assíntota (a função se aproxima, mas nunca toca o eixo $y$).

*Exemplo*: $f(x) = \log_2 x$

### Teoria dos Logaritmos

**Propriedades Operatórias:**
1.  **Logaritmo do Produto**: $\log_a (x \cdot y) = \log_a x + \log_a y$
2.  **Logaritmo do Quociente**: $\log_a \left(\frac{x}{y}\right) = \log_a x - \log_a y$
3.  **Logaritmo da Potência**: $\log_a x^n = n \cdot \log_a x$
4.  **Mudança de Base**: $\log_a x = \frac{\log_b x}{\log_b a}$

**Logaritmos Especiais:**
-   **Logaritmo Decimal**: Base 10 ($\log x = \log_{10} x$)
-   **Logaritmo Neperiano (Natural)**: Base $e$ (número de Euler, $e \approx 2.718$) ($\ln x = \log_e x$)

### Uso de Logaritmos em Cálculos e Modelagem de Problemas

Logaritmos são ferramentas poderosas para resolver equações exponenciais e modelar fenômenos que crescem ou decaem exponencialmente.

-   **Crescimento Populacional**: $P(t) = P_0 \cdot e^{kt}$
-   **Juros Compostos**: $M = C(1+i)^t$
-   **Decaimento Radioativo**: $Q(t) = Q_0 \cdot \left(\frac{1}{2}\right)^{\frac{t}{T}}$ (onde $T$ é a meia-vida)
-   **Escalas Logarítmicas**: pH (química), escala Richter (terremotos), decibéis (som).

**Resolução de equações exponenciais com logaritmos:**
Para resolver $a^x = b$, aplica-se logaritmo em ambos os lados:
$\log a^x = \log b \Rightarrow x \log a = \log b \Rightarrow x = \frac{\log b}{\log a}$

---

## Exercícios Estilo Vunesp

**Questão 1 (Vunesp Adaptada):**
Seja a função $f(x) = 3^x$. É correto afirmar que:

a) A função é decrescente e sua imagem é $\mathbb{R}$.
b) O gráfico da função intercepta o eixo $y$ no ponto $(0, 3)$.
c) A base da função é $a = 3$, portanto, a função é crescente e sua imagem é $\mathbb{R}_+$.
d) O domínio da função é $\mathbb{R}_+$ e ela passa pelo ponto $(1, 0)$.
e) O eixo $x$ é uma assíntota vertical para o gráfico da função.

**Resolução:**
Vamos analisar cada alternativa:
- a) Incorreta. A base $3 > 1$, então a função é crescente. A imagem é $\mathbb{R}_+$, não $\mathbb{R}$.
- b) Incorreta. Quando $x=0$, $f(0) = 3^0 = 1$. O gráfico intercepta o eixo $y$ em $(0, 1)$.
- c) Correta. A base $a = 3$ é maior que 1, caracterizando uma função exponencial crescente. A imagem de uma função exponencial é sempre o conjunto dos reais positivos ($y > 0$).
- d) Incorreta. O domínio da função exponencial é $\mathbb{R}$. Ela passa pelo ponto $(0, 1)$, não $(1, 0)$.
- e) Incorreta. O eixo $x$ ($y=0$) é uma assíntota horizontal, não vertical.

**Alternativa Correta: c)**

---

**Questão 2 (Vunesp Adaptada):**
Sabendo que $\log_{10} 2 = 0.3$ e $\log_{10} 3 = 0.48$, qual é o valor de $\log_{10} 12$? 

a) 0.78
b) 0.60
c) 1.08
d) 1.20
e) 0.96

**Resolução:**
Podemos reescrever 12 como $2^2 \cdot 3$.
Então, $\log_{10} 12 = \log_{10} (2^2 \cdot 3)$.
Usando a propriedade do logaritmo do produto: $\log_{10} (2^2 \cdot 3) = \log_{10} 2^2 + \log_{10} 3$.
Usando a propriedade do logaritmo da potência: $\log_{10} 2^2 + \log_{10} 3 = 2 \cdot \log_{10} 2 + \log_{10} 3$.
Substituindo os valores dados:
$2 \cdot (0.3) + 0.48 = 0.6 + 0.48 = 1.08$.

**Alternativa Correta: c)**
