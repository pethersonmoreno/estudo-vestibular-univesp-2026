# Diferentes Métodos para Obtenção de Áreas <span class="tag-media-frequencia">⚠️ FREQUÊNCIA MÉDIA</span>

A área de uma figura geométrica é a medida de sua superfície. Na matemática, existem diversos métodos para calcular áreas de diferentes figuras planas, desde as mais simples até as mais complexas. Dominar essas fórmulas e técnicas é crucial para a resolução de problemas de geometria em vestibulares.

## 7.8. Diferentes Métodos para Obtenção de Áreas

### 1. Áreas de Figuras Planas Básicas

-   **Quadrado**: $A = lado^2 = L^2$
-   **Retângulo**: $A = base \times altura = b \times h$
-   **Paralelogramo**: $A = base \times altura = b \times h$
-   **Triângulo**: $A = \frac{base \times altura}{2} = \frac{b \times h}{2}$
    -   **Triângulo Equilátero**: $A = \frac{L^2 \sqrt{3}}{4}$
    -   **Fórmula de Heron** (para qualquer triângulo, conhecendo os três lados $a, b, c$):
        $A = \sqrt{s(s-a)(s-b)(s-c)}$, onde $s = \frac{a+b+c}{2}$ (semiperímetro).
    -   **Usando Seno**: $A = \frac{1}{2}ab \sin C$ (onde $a$ e $b$ são dois lados e $C$ é o ângulo entre eles).
-   **Trapézio**: $A = \frac{(BaseMaior + BaseMenor) \times altura}{2} = \frac{(B+b) \times h}{2}$
-   **Losango**: $A = \frac{DiagonalMaior \times DiagonalMenor}{2} = \frac{D \times d}{2}$
-   **Círculo**: $A = \pi r^2$

### 2. Áreas de Polígonos Regulares

Para qualquer polígono regular (com $n$ lados iguais e $n$ ângulos internos iguais), a área pode ser calculada usando o apótema ($a_p$) e o perímetro ($P$):

$A = \frac{P \times a_p}{2}$

Onde o perímetro $P = n \times L$ (número de lados $\times$ medida do lado).

### 3. Áreas de Figuras Planas por Decomposição

Figuras complexas podem ter suas áreas calculadas dividindo-as em figuras mais simples (quadrados, retângulos, triângulos, trapézios) cujas áreas são mais fáceis de calcular. A área total é a soma das áreas das partes.

*Exemplo*: Uma figura em forma de "L" pode ser decomposta em dois retângulos.

### 4. Áreas de Figuras Planas por Diferença

Em alguns casos, é mais fácil calcular a área de uma figura maior que contém a figura de interesse e subtrair a área das partes que não pertencem à figura de interesse.

*Exemplo*: Calcular a área de uma coroa circular (região entre dois círculos concêntricos) subtraindo a área do círculo menor da área do círculo maior.

### 5. Área de Setor Circular e Segmento Circular

-   **Setor Circular**: Uma "fatia" do círculo. Sua área é proporcional ao ângulo central.
    $A_{setor} = \frac{\alpha}{360^\circ} \times \pi r^2$ (onde $\alpha$ é o ângulo em graus)
    ou $A_{setor} = \frac{1}{2} r^2 \alpha_{rad}$ (onde $\alpha_{rad}$ é o ângulo em radianos).

-   **Segmento Circular**: A área entre uma corda e o arco correspondente. Pode ser calculada subtraindo a área do triângulo formado pelo centro e os extremos da corda da área do setor circular correspondente.
    $A_{segmento} = A_{setor} - A_{triângulo}$

### 6. Área de Figuras no Plano Cartesiano

Para um polígono cujos vértices são dados por coordenadas $(x_1, y_1), (x_2, y_2), ..., (x_n, y_n)$ no plano cartesiano, pode-se usar a **fórmula do determinante** (ou fórmula de shoelace/cadarço):

$A = \frac{1}{2} | (x_1y_2 + x_2y_3 + ... + x_ny_1) - (y_1x_2 + y_2x_3 + ... + y_nx_1) |$

---

## Exercícios Estilo Vunesp

**Questão 1 (Vunesp Adaptada):**
Um terreno tem o formato de um trapézio com bases de 10 metros e 16 metros, e altura de 5 metros. Qual é a área total desse terreno?

a) 65 m²
b) 70 m²
c) 75 m²
d) 80 m²
e) 85 m²

**Resolução:**
A fórmula para a área de um trapézio é $A = \frac{(B+b) \times h}{2}$.
Dados: Base Maior ($B$) = 16 m, Base Menor ($b$) = 10 m, altura ($h$) = 5 m.
$A = \frac{(16 + 10) \times 5}{2}$
$A = \frac{26 \times 5}{2}$
$A = \frac{130}{2}$
$A = 65$ m²

**Alternativa Correta: a)**

---

**Questão 2 (Vunesp Adaptada):**
Considere um setor circular de um círculo de raio 6 cm, com um ângulo central de 60°. Qual é a área desse setor circular? (Utilize $\pi \approx 3.14$)

a) $6.28$ cm²
b) $12.56$ cm²
c) $18.84$ cm²
d) $36$ cm²
e) $113.04$ cm²

**Resolução:**
A fórmula para a área de um setor circular é $A_{setor} = \frac{\alpha}{360^\circ} \times \pi r^2$.
Dados: $\alpha = 60^\circ$, $r = 6$ cm.
$A_{setor} = \frac{60^\circ}{360^\circ} \times \pi (6^2)$
$A_{setor} = \frac{1}{6} \times \pi (36)$
$A_{setor} = 6\pi$
Usando $\pi \approx 3.14$:
$A_{setor} = 6 \times 3.14 = 18.84$ cm²

**Alternativa Correta: c)**
