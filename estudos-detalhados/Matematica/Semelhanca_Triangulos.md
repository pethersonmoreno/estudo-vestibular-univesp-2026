# Semelhança de Triângulos [⚠️ FREQUÊNCIA MÉDIA]

A semelhança de triângulos é um conceito essencial na geometria, permitindo estabelecer relações de proporcionalidade entre figuras que possuem a mesma forma, mas tamanhos diferentes. É amplamente utilizado em problemas de geometria, escala e proporções, sendo um tema recorrente em vestibulares como o da Vunesp.

## 7.5. Semelhança de Triângulos

Dois triângulos são ditos **semelhantes** se eles têm a mesma forma, mas não necessariamente o mesmo tamanho. Isso significa que um triângulo pode ser uma ampliação ou uma redução do outro. Para que dois triângulos sejam semelhantes, duas condições devem ser satisfeitas:

1.  **Ângulos Correspondentes Congruentes (iguais)**: Os ângulos internos dos dois triângulos, tomados em correspondência, devem ter as mesmas medidas.
2.  **Lados Correspondentes Proporcionais**: As medidas dos lados correspondentes devem formar uma razão constante, chamada de **razão de semelhança (k)**.

Se $\triangle ABC \sim \triangle DEF$, então:
-   $\angle A = \angle D$, $\angle B = \angle E$, $\angle C = \angle F$
-   $\frac{AB}{DE} = \frac{BC}{EF} = \frac{AC}{DF} = k$

### Critérios de Semelhança de Triângulos

Assim como na congruência, existem critérios mínimos para determinar a semelhança entre triângulos:

1.  **Critério A.A. (Ângulo, Ângulo)**:
    Se dois triângulos possuem dois ângulos correspondentes congruentes, então eles são semelhantes. (Consequentemente, o terceiro ângulo também será congruente).
    *Exemplo*: Se um triângulo tem ângulos de 30° e 70°, e outro triângulo também tem ângulos de 30° e 70°, eles são semelhantes.

2.  **Critério L.L.L. (Lado, Lado, Lado)**:
    Se dois triângulos possuem os três lados correspondentes proporcionais, então eles são semelhantes.
    *Exemplo*: Se os lados de um triângulo são (3, 4, 5) e os de outro são (6, 8, 10), a razão de proporcionalidade é 2, e eles são semelhantes.

3.  **Critério L.A.L. (Lado, Ângulo, Lado)**:
    Se dois triângulos possuem dois lados correspondentes proporcionais e o ângulo entre eles (ângulo compreendido) congruente, então eles são semelhantes.
    *Exemplo*: Se dois triângulos têm lados de 6 cm e 8 cm formando um ângulo de 45°, e outro tem lados de 12 cm e 16 cm formando um ângulo de 45°, eles são semelhantes.

### Aplicações da Semelhança de Triângulos

-   **Cálculo de Medidas Desconhecidas**: Usada para encontrar a altura de objetos (árvores, edifícios) a partir de suas sombras, ou distâncias inacessíveis.
-   **Escalas**: Mapas, plantas e maquetes são aplicações diretas da semelhança, onde a razão de semelhança é a escala.
-   **Geometria Analítica e Plana**: Resolução de diversos problemas que envolvem figuras proporcionais.

**Propriedades Importantes:**
-   A razão entre as perímetros de dois triângulos semelhantes é igual à razão de semelhança ($k$).
-   A razão entre as áreas de dois triângulos semelhantes é igual ao quadrado da razão de semelhança ($k^2$).

---

## Exercícios Estilo Vunesp

**Questão 1 (Vunesp Adaptada):**
Para determinar a altura de um prédio, um estudante de 1,60 m de altura observa que sua sombra mede 2 m. No mesmo instante, a sombra do prédio mede 25 m. Qual é a altura do prédio?

a) 15 m
b) 18 m
c) 20 m
d) 22 m
e) 24 m

**Resolução:**
Podemos formar dois triângulos semelhantes: um com o estudante e sua sombra, e outro com o prédio e sua sombra. A luz do sol atinge ambos formando o mesmo ângulo, e tanto o estudante quanto o prédio formam um ângulo reto com o chão. Portanto, os triângulos são semelhantes pelo critério A.A.

Seja $H$ a altura do prédio e $S_H$ sua sombra.
Seja $h$ a altura do estudante e $S_h$ sua sombra.

Podemos estabelecer a proporção:
$\frac{H}{S_H} = \frac{h}{S_h}$
$\frac{H}{25} = \frac{1.60}{2}$

Agora, resolvemos para $H$:
$H = 25 \times \frac{1.60}{2}$
$H = 25 \times 0.8$
$H = 20$ m

**Alternativa Correta: c)**

---

**Questão 2 (Vunesp Adaptada):**
Considere dois triângulos semelhantes, $\triangle ABC$ e $\triangle A'B'C'$. Sabe-se que os lados $AB = 6$ cm e $A'B' = 9$ cm. Se a área do triângulo $\triangle ABC$ é de 16 cm², qual é a área do triângulo $\triangle A'B'C'$?

a) 24 cm²
b) 32 cm²
c) 36 cm²
d) 48 cm²
e) 54 cm²

**Resolução:**
Primeiro, calculamos a razão de semelhança ($k$) entre os lados dos triângulos:
$k = \frac{A'B'}{AB} = \frac{9}{6} = \frac{3}{2}$

Sabemos que a razão entre as áreas de triângulos semelhantes é igual ao quadrado da razão de semelhança ($k^2$).
$\frac{\text{Área}(A'B'C')}{\text{Área}(ABC)} = k^2$
$\frac{\text{Área}(A'B'C')}{16} = \left(\frac{3}{2}\right)^2$
$\frac{\text{Área}(A'B'C')}{16} = \frac{9}{4}$

Agora, resolvemos para a Área$(A'B'C')$:
$\text{Área}(A'B'C') = 16 \times \frac{9}{4}$
$\text{Área}(A'B'C') = 4 \times 9$
$\text{Área}(A'B'C') = 36$ cm²

**Alternativa Correta: c)**
