# Geometria Plana: Coordenadas, Plano Cartesiano, Distância e Ponto Médio

Vamos explorar a geometria analítica, que usa um sistema de coordenadas para representar figuras geométricas e resolver problemas algebricamente. Abordaremos o plano cartesiano, distância entre pontos e o ponto médio de um segmento.

## Plano Cartesiano

O **plano cartesiano** é um sistema de coordenadas bidimensional formado por duas retas numéricas perpendiculares que se intersectam na origem (ponto O). Estas retas são chamadas de eixos:
*   **Eixo x (abscissas):** A reta horizontal.
*   **Eixo y (ordenadas):** A reta vertical.

Qualquer ponto P no plano pode ser univocamente identificado por um par ordenado (x, y), onde 'x' é a coordenada horizontal e 'y' é a coordenada vertical.

![Plano Cartesiano](https://upload.wikimedia.org/wikipedia/commons/thumb/8/87/Cartesian_coordinates_2D.svg/440px-Cartesian_coordinates_2D.svg.png)

## Distância entre Dois Pontos

A distância entre dois pontos $A = (x_1, y_1)$ e $B = (x_2, y_2)$ no plano cartesiano pode ser calculada utilizando o Teorema de Pitágoras. Visualmente, a diferença nas coordenadas x forma um cateto, e a diferença nas coordenadas y forma o outro cateto de um triângulo retângulo, onde a distância AB é a hipotenusa.

Fórmula: $$d(A, B) = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}$$

**Exemplo:**
*   Calcule a distância entre os pontos A(1, 2) e B(4, 6).
    *   $x_1 = 1, y_1 = 2$
    *   $x_2 = 4, y_2 = 6$
    *   $d(A, B) = \sqrt{(4 - 1)^2 + (6 - 2)^2}$
    *   $d(A, B) = \sqrt{(3)^2 + (4)^2}$
    *   $d(A, B) = \sqrt{9 + 16}$
    *   $d(A, B) = \sqrt{25}$
    *   $d(A, B) = 5$

## Ponto Médio de um Segmento de Reta

O **ponto médio (M)** de um segmento de reta que liga os pontos $A = (x_1, y_1)$ e $B = (x_2, y_2)$ é o ponto que divide o segmento em duas partes iguais. Suas coordenadas são a média aritmética das coordenadas correspondentes dos pontos A e B.

Fórmula: $$M = \left( \frac{x_1 + x_2}{2}, \frac{y_1 + y_2}{2} \right)$$

**Exemplo:**
*   Determine o ponto médio do segmento que liga A(1, 2) e B(5, 8).
    *   $x_M = \frac{1 + 5}{2} = \frac{6}{2} = 3$
    *   $y_M = \frac{2 + 8}{2} = \frac{10}{2} = 5$
    *   O ponto médio é M(3, 5).

## Exercícios Estilo Vunesp

**Exercício 1 (VUNESP - Adaptado)**

Considere os pontos P(2, -1) e Q(5, 3) no plano cartesiano. A distância entre P e Q é:

A) $\sqrt{7}$

B) $\sqrt{13}$

C) 5

D) $\sqrt{25}$

E) $\sqrt{34}$

**Resolução:**
*   $d(P, Q) = \sqrt{(5 - 2)^2 + (3 - (-1))^2}$
*   $d(P, Q) = \sqrt{(3)^2 + (3 + 1)^2}$
*   $d(P, Q) = \sqrt{9 + (4)^2}$
*   $d(P, Q) = \sqrt{9 + 16}$
*   $d(P, Q) = \sqrt{25} = 5$

**Resposta:** C

---

**Exercício 2 (VUNESP - Adaptado)**

O ponto médio do segmento de reta que une os pontos A(-3, 4) e B(7, -2) é:

A) (2, 1)

B) (1, 2)

C) (5, -3)

D) (-5, 3)

E) (4, 2)

**Resolução:**
*   $x_M = \frac{-3 + 7}{2} = \frac{4}{2} = 2$
*   $y_M = \frac{4 + (-2)}{2} = \frac{2}{2} = 1$
*   O ponto médio é M(2, 1).

**Resposta:** A
