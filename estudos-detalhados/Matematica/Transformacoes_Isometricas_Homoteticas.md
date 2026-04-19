# Transformações Isométricas e Homotéticas <span class="tag-media-frequencia">[⚠️ FREQUÊNCIA MÉDIA]</span>

As transformações geométricas são operações que mudam a posição ou o tamanho de figuras no plano ou no espaço. Dentre elas, destacam-se as isometrias (que preservam medidas) e as homotetias (que alteram o tamanho, mas preservam a forma). O domínio desses conceitos é fundamental para a geometria e para questões de vestibular da Vunesp.

## 7.3. Transformações Isométricas e Homotéticas

### Transformações Isométricas (Isometrias)

As **transformações isométricas** (do grego *iso* = igual; *metron* = medida) são aquelas que preservam as distâncias e os ângulos entre os pontos de uma figura. Isso significa que a figura original (pré-imagem) e a figura transformada (imagem) são **congruentes**, ou seja, têm a mesma forma e o mesmo tamanho. São exemplos de isometrias:

1.  **Translação**: Deslocamento de uma figura no plano em uma determinada direção, sentido e distância, sem girar ou espelhar. Todos os pontos da figura se movem paralelamente e na mesma medida.
    *Exemplo*: Mover um quadrado 5 unidades para a direita.

2.  **Rotação**: Giro de uma figura em torno de um ponto fixo (centro de rotação) por um determinado ângulo e sentido (horário ou anti-horário). A forma e o tamanho da figura permanecem os mesmos.
    *Exemplo*: Girar um triângulo 90° no sentido horário em torno da origem.

3.  **Reflexão (ou Simetria Axial)**: Inversão de uma figura em relação a uma reta (eixo de reflexão). A figura resultante é uma "imagem espelhada" da figura original. Embora a orientação mude, as medidas são preservadas.
    *Exemplo*: Refletir um polígono em relação ao eixo $y$.

**Características Comuns das Isometrias:**
-   Preservam a forma e o tamanho (congruência).
-   Preservam as distâncias entre os pontos.
-   Preservam os ângulos.
-   A orientação pode ser preservada (translação, rotação) ou invertida (reflexão).

### Transformações Homotéticas (Homotetias)

A **transformação homotética** (do grego *homo* = igual; *tetos* = posição) é uma transformação que altera o tamanho de uma figura, mas preserva sua forma. Isso significa que a figura original e a figura transformada são **semelhantes**.

A homotetia é definida por um **centro (P)** e uma **razão de proporcionalidade (k)**.

-   Cada ponto $A$ da figura original é transformado em um ponto $A'$ tal que $P, A, A'$ são colineares e a distância de $P$ a $A'$ é $|k|$ vezes a distância de $P$ a $A$. Ou seja, $\vec{PA'} = k \cdot \vec{PA}$.

**Características:**
-   **Preserva a forma**, mas altera o tamanho (resulta em figuras semelhantes).
-   **Preserva os ângulos**.
-   **Não preserva as distâncias** entre os pontos (a menos que $|k|=1$). As distâncias são multiplicadas por $|k|$.
-   As retas que unem os pontos correspondentes da figura original e da figura transformada passam todas pelo centro da homotetia.

**Tipos de Homotetia:**
-   **Homotetia direta (k > 0)**: A figura original e a transformada estão do mesmo lado em relação ao centro da homotetia.
    -   Se $k > 1$: A figura é ampliada.
    -   Se $0 < k < 1$: A figura é reduzida.
    -   Se $k = 1$: A figura é idêntica à original (transformação identidade).
-   **Homotetia inversa (k < 0)**: A figura original e a transformada estão em lados opostos em relação ao centro da homotetia.
    -   Se $k < -1$: A figura é ampliada e invertida.
    -   Se $-1 < k < 0$: A figura é reduzida e invertida.
    -   Se $k = -1$: A figura é invertida, mas com o mesmo tamanho (simetria central).

---

## Exercícios Estilo Vunesp

**Questão 1 (Vunesp Adaptada):**
Um designer gráfico está trabalhando na criação de um logotipo e precisa aplicar uma transformação em um triângulo. Ele decide girar o triângulo em 90° no sentido anti-horário em torno de um ponto fixo. Essa transformação geométrica é um exemplo de:

a) Homotetia inversa, pois altera o tamanho da figura.

b) Reflexão, pois a figura é espelhada em relação a um eixo.

c) Translação, pois a figura é apenas deslocada em linha reta.

d) Rotação, uma transformação isométrica que mantém a forma e o tamanho da figura.

e) Dilatação, uma transformação que aumenta a área, mas não a forma.

**Resolução:**
Vamos analisar as alternativas:
- a) Incorreta. Homotetia altera o tamanho.
- b) Incorreta. Reflexão espelha.
- c) Incorreta. Translação desloca sem girar.
- d) Correta. A rotação é uma transformação isométrica que gira a figura em torno de um ponto, preservando sua forma e tamanho.
- e) Incorreta. Dilatação não é um termo comum em transformações geométricas básicas para esse contexto, e rotação não altera a área.

**Alternativa Correta: d)**

---

**Questão 2 (Vunesp Adaptada):**
Considere uma figura geométrica que sofre uma homotetia de centro na origem $(0,0)$ e razão $k = 2$. Se o comprimento de um dos lados da figura original era de 5 cm, qual será o comprimento do lado correspondente na figura transformada?

a) 2.5 cm

b) 5 cm

c) 10 cm

d) 15 cm

e) 20 cm

**Resolução:**
Na homotetia, as distâncias (comprimentos dos lados) são multiplicadas pelo módulo da razão de proporcionalidade $|k|$.
Neste caso, $k = 2$, então $|k| = 2$.
Comprimento do lado transformado = Comprimento do lado original $\times |k|$
Comprimento do lado transformado = $5 \text{ cm} \times 2 = 10 \text{ cm}$.

**Alternativa Correta: c)**
