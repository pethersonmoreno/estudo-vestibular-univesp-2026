# Trigonometria <span class="tag-media-frequencia">⚠️ FREQUÊNCIA MÉDIA</span>

A Trigonometria é o ramo da matemática que estuda as relações entre os ângulos e os lados dos triângulos. É fundamental para diversas áreas da ciência e engenharia, e suas aplicações são vastas, desde a navegação até a física e a engenharia. No vestibular, questões de trigonometria são comuns e exigem um bom domínio dos conceitos e fórmulas.

## 6.1. Arcos e Ângulos

-   **Ângulo**: Abertura formada por duas semirretas que partem de um mesmo ponto (vértice).
-   **Arco**: Parte de uma circunferência. A medida de um arco é igual à medida do ângulo central que o subtende.
-   **Unidades de Medida**: 
    -   **Graus ($^\circ$)**: Uma volta completa = 360°.
    -   **Radiano (rad)**: Medida do arco cujo comprimento é igual ao raio da circunferência. Uma volta completa = $2\pi$ rad. A relação é $180^\circ = \pi$ rad.
-   **Ciclo Trigonométrico**: Uma circunferência de raio 1 centrada na origem de um plano cartesiano, usada para representar os ângulos e as funções trigonométricas. Os ângulos são medidos a partir do eixo $x$ positivo no sentido anti-horário.

## 6.2. Funções Seno e Cosseno

Para um ângulo $\theta$ no ciclo trigonométrico, definimos:
-   **Seno ($\sin \theta$)**: Coordenada $y$ do ponto na circunferência. Varia de -1 a 1.
-   **Cosseno ($\cos \theta$)**: Coordenada $x$ do ponto na circunferência. Varia de -1 a 1.
-   **Tangente ($\tan \theta$)**: Razão $\frac{\sin \theta}{\cos \theta}$. Não definida quando $\cos \theta = 0$ ($90^\circ + k \cdot 180^\circ$).

**Relação Fundamental da Trigonometria**: $\sin^2 \theta + \cos^2 \theta = 1$

### Gráficos das Funções Seno e Cosseno

-   **Função Seno ($f(x) = \sin x$)**: Periódica com período $2\pi$. O gráfico é uma onda que oscila entre -1 e 1.
-   **Função Cosseno ($f(x) = \cos x$)**: Periódica com período $2\pi$. O gráfico é uma onda que oscila entre -1 e 1, defasada em relação ao seno.

## 6.3. Resolução de Problemas Envolvendo Equações e Inequações Trigonométricas

### Equações Trigonométricas

Buscam-se os valores do ângulo que satisfazem a igualdade. É importante considerar a periodicidade das funções.
*Exemplo*: $\sin x = \frac{1}{2}$. As soluções no intervalo $[0, 2\pi)$ são $x = \frac{\pi}{6}$ e $x = \frac{5\pi}{6}$. A solução geral é $x = \frac{\pi}{6} + 2k\pi$ ou $x = \frac{5\pi}{6} + 2k\pi$, onde $k \in \mathbb{Z}$.

### Inequações Trigonométricas

Busca-se o intervalo de valores do ângulo que satisfazem a desigualdade. É essencial analisar o gráfico da função ou o ciclo trigonométrico.
*Exemplo*: $\cos x > 0$. No intervalo $[0, 2\pi)$, as soluções são $0 \le x < \frac{\pi}{2}$ ou $\frac{3\pi}{2} < x \le 2\pi$.

## 6.4. Resoluções de Triângulos Retângulos (Seno, Cosseno e Tangente)

Em um **triângulo retângulo**, as funções trigonométricas de um ângulo agudo são definidas pelas razões entre os lados:
-   **Seno**: $\sin \theta = \frac{\text{cateto oposto}}{\text{hipotenusa}}$
-   **Cosseno**: $\cos \theta = \frac{\text{cateto adjacente}}{\text{hipotenusa}}$
-   **Tangente**: $\tan \theta = \frac{\text{cateto oposto}}{\text{cateto adjacente}}$

*Valores Notáveis*: 
| Ângulo | Seno | Cosseno | Tangente |
|---|---|---|---|
| $30^\circ$ | $1/2$ | $\sqrt{3}/2$ | $\sqrt{3}/3$ |
| $45^\circ$ | $\sqrt{2}/2$ | $\sqrt{2}/2$ | 1 |
| $60^\circ$ | $\sqrt{3}/2$ | $1/2$ | $\sqrt{3}$ |

## Teorema dos Senos

Em qualquer triângulo (não necessariamente retângulo), a razão entre a medida de um lado e o seno do ângulo oposto a esse lado é constante e igual ao diâmetro da circunferência circunscrita ao triângulo.
$\frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C} = 2R$
Onde $a, b, c$ são os lados, $A, B, C$ são os ângulos opostos e $R$ é o raio da circunferência circunscrita.

## Teorema dos Cossenos

Em qualquer triângulo, o quadrado da medida de um lado é igual à soma dos quadrados das medidas dos outros dois lados, menos o dobro do produto dessas medidas pelo cosseno do ângulo formado por eles.
$a^2 = b^2 + c^2 - 2bc \cos A$
$b^2 = a^2 + c^2 - 2ac \cos B$
$c^2 = a^2 + b^2 - 2ab \cos C$

## Resolução de Triângulos Obtusângulos

Triângulos obtusângulos (com um ângulo maior que 90°) também podem ser resolvidos usando o Teorema dos Senos e o Teorema dos Cossenos. Atenção ao sinal do cosseno de ângulos obtusos, que é negativo ($\cos(180^\circ - \theta) = -\cos \theta$).

---

## Exercícios Estilo Vunesp

**Questão 1 (Vunesp Adaptada):**
Um topógrafo precisa medir a altura de uma árvore. Ele se posiciona a 20 metros da base da árvore e, utilizando um teodolito, mede o ângulo de elevação do topo da árvore como sendo 30°. Desprezando a altura do teodolito e do topógrafo, qual a altura da árvore? (Considere $\tan 30^\circ = \frac{\sqrt{3}}{3}$ e $\sqrt{3} \approx 1.73$)

a) 10 m
b) $10\sqrt{3}$ m
c) 20 m
d) $\frac{20\sqrt{3}}{3}$ m
e) $20\sqrt{3}$ m

**Resolução:**
Consideramos um triângulo retângulo onde:
-   Cateto adjacente ao ângulo de 30° é a distância do topógrafo à árvore = 20 m.
-   Cateto oposto ao ângulo de 30° é a altura da árvore = $h$.
-   A relação que envolve cateto oposto e cateto adjacente é a tangente.
$\tan 30^\circ = \frac{\text{cateto oposto}}{\text{cateto adjacente}} = \frac{h}{20}$
$\frac{\sqrt{3}}{3} = \frac{h}{20}$
$3h = 20\sqrt{3}$
$h = \frac{20\sqrt{3}}{3}$ m

**Alternativa Correta: d)**

---

**Questão 2 (Vunesp Adaptada):**
Em um triângulo $ABC$, os lados $AB = 8$ cm e $AC = 10$ cm. O ângulo entre esses dois lados (ângulo $A$) mede $60^\circ$. Qual é a medida do lado $BC$? (Considere $\cos 60^\circ = \frac{1}{2}$)

a) $\sqrt{20}$ cm
b) $\sqrt{24}$ cm
c) $\sqrt{84}$ cm
d) $\sqrt{100}$ cm
e) $\sqrt{164}$ cm

**Resolução:**
Utilizamos o Teorema dos Cossenos. Seja $a$ o lado $BC$, $b$ o lado $AC$ e $c$ o lado $AB$.
$a^2 = b^2 + c^2 - 2bc \cos A$
$a^2 = 10^2 + 8^2 - 2(10)(8) \cos 60^\circ$
$a^2 = 100 + 64 - 2(80) \left(\frac{1}{2}\right)$
$a^2 = 164 - 160 \left(\frac{1}{2}\right)$
$a^2 = 164 - 80$
$a^2 = 84$
$a = \sqrt{84}$ cm

**Alternativa Correta: c)**
