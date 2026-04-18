# Ladrilhamento no Plano (Tesselação) [⚠️ FREQUÊNCIA MÉDIA]

O ladrilhamento, também conhecido como pavimentação ou tesselação, é o processo de cobrir uma superfície plana com figuras geométricas (ladrilhos) sem deixar espaços vazios e sem sobreposição. Este conceito, presente na arte e na arquitetura, tem fundamentos matemáticos importantes na geometria plana e é um tópico que pode aparecer em questões de vestibular.

## 7.9. Resolver Problemas sobre Ladrilhamento no Plano

### O que é Ladrilhamento (Tesselação)?

Um **ladrilhamento** é uma cobertura do plano por uma ou mais figuras geométricas que se encaixam perfeitamente, sem falhas e sem se sobrepor. Os ladrilhamentos mais estudados são aqueles feitos por polígonos regulares.

### Ladrilhamento com Polígonos Regulares

Para que um único tipo de polígono regular possa ladrilhar o plano, a soma dos ângulos internos dos polígonos que se encontram em um vértice deve ser exatamente $360^\circ$. Se a soma for menor, haverá espaços; se for maior, haverá sobreposição.

-   **Ângulo Interno de um Polígono Regular**: $A_i = \frac{(n-2) \times 180^\circ}{n}$, onde $n$ é o número de lados do polígono.

Vamos verificar quais polígonos regulares podem ladrilhar o plano:

1.  **Triângulo Equilátero (n=3)**:
    -   Ângulo interno: $A_i = \frac{(3-2) \times 180^\circ}{3} = \frac{1 \times 180^\circ}{3} = 60^\circ$.
    -   Número de triângulos em um vértice para completar $360^\circ$: $\frac{360^\circ}{60^\circ} = 6$. 
    -   **Conclusão: Sim, o triângulo equilátero pode ladrilhar o plano.**

2.  **Quadrado (n=4)**:
    -   Ângulo interno: $A_i = \frac{(4-2) \times 180^\circ}{4} = \frac{2 \times 180^\circ}{4} = 90^\circ$.
    -   Número de quadrados em um vértice para completar $360^\circ$: $\frac{360^\circ}{90^\circ} = 4$.
    -   **Conclusão: Sim, o quadrado pode ladrilhar o plano.**

3.  **Hexágono Regular (n=6)**:
    -   Ângulo interno: $A_i = \frac{(6-2) \times 180^\circ}{6} = \frac{4 \times 180^\circ}{6} = 120^\circ$.
    -   Número de hexágonos em um vértice para completar $360^\circ$: $\frac{360^\circ}{120^\circ} = 3$.
    -   **Conclusão: Sim, o hexágono regular pode ladrilhar o plano.**

4.  **Pentágono Regular (n=5)**:
    -   Ângulo interno: $A_i = \frac{(5-2) \times 180^\circ}{5} = \frac{3 \times 180^\circ}{5} = 108^\circ$.
    -   Número de pentágonos em um vértice: $\frac{360^\circ}{108^\circ} \approx 3.33$. Não é um número inteiro.
    -   **Conclusão: Não, o pentágono regular não pode ladrilhar o plano sozinho.**

**Portanto, os únicos polígonos regulares que podem ladrilhar o plano sozinho são o triângulo equilátero, o quadrado e o hexágono regular.**

### Ladrilhamento com Polígonos Não Regulares ou Mistos

-   É possível ladrilhar o plano com polígonos não regulares (ex: retângulos, paralelogramos, triângulos quaisquer).
-   Também é possível realizar ladrilhamentos utilizando combinações de diferentes polígonos regulares, desde que a soma dos ângulos dos polígonos que se encontram em cada vértice seja $360^\circ$. Esses são chamados de **ladrilhamentos semiregulares** ou **tesselações de Arquimedes**.

*Exemplo*: Uma combinação de quadrados e triângulos equiláteros pode formar um ladrilhamento semiregular.

### Áreas em Ladrilhamentos

Para resolver problemas envolvendo áreas em ladrilhamentos:
-   Calcule a área de um único ladrilho.
-   Multiplique pela quantidade de ladrilhos, se for um número fixo.
-   Se a área da superfície a ser coberta é dada, divida pela área de um ladrilho para encontrar a quantidade necessária (ajustando para perdas ou cortes).

---

## Exercícios Estilo Vunesp

**Questão 1 (Vunesp Adaptada):**
Um arquiteto deseja ladrilhar uma sala utilizando apenas um tipo de polígono regular. Para que o ladrilhamento seja perfeito, sem deixar espaços vazios nem sobreposições, o polígono escolhido deve ter seu ângulo interno como um divisor de $360^\circ$. Dos polígonos regulares listados abaixo, qual NÃO seria adequado para ladrilhar o plano sozinho?

a) Triângulo equilátero
b) Quadrado
c) Hexágono regular
d) Pentágono regular
e) Nenhuma das alternativas anteriores.

**Resolução:**
Vamos calcular o ângulo interno de cada polígono:
-   Triângulo equilátero: $60^\circ$ ($360^\circ / 6 = 60^\circ$)
-   Quadrado: $90^\circ$ ($360^\circ / 4 = 90^\circ$)
-   Hexágono regular: $120^\circ$ ($360^\circ / 3 = 120^\circ$)
-   Pentágono regular: $A_i = \frac{(5-2) \times 180^\circ}{5} = \frac{3 \times 180^\circ}{5} = 108^\circ$. 
    $360^\circ / 108^\circ \approx 3.33...$, que não é um número inteiro. Portanto, o pentágono regular não pode ladrilhar o plano sozinho.

**Alternativa Correta: d)**

---

**Questão 2 (Vunesp Adaptada):**
Uma parede retangular de 3 metros de altura por 4 metros de comprimento será totalmente revestida com ladrilhos quadrados de 20 cm de lado. Quantos ladrilhos serão necessários para cobrir toda a parede?

a) 200
b) 300
c) 350
d) 400
e) 450

**Resolução:**
Primeiro, calculamos a área da parede e a área de um ladrilho, ambos na mesma unidade de medida.

**Área da Parede:**
-   Altura = 3 m = 300 cm
-   Comprimento = 4 m = 400 cm
-   Área da Parede ($A_{parede}$) = $300 \text{ cm} \times 400 \text{ cm} = 120.000 \text{ cm}^2$

**Área de um Ladrilho:**
-   Lado do ladrilho = 20 cm
-   Área de um Ladrilho ($A_{ladrilho}$) = $20^2 \text{ cm}^2 = 400 \text{ cm}^2$

**Número de Ladrilhos:**
Número de Ladrilhos = $\frac{A_{parede}}{A_{ladrilho}} = \frac{120.000}{400} = \frac{1200}{4} = 300$

**Alternativa Correta: b)**
