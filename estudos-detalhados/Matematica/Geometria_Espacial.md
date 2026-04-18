# Geometria Espacial <span class="tag-media-frequencia">⚠️ FREQUÊNCIA MÉDIA</span>

A Geometria Espacial estuda as formas no espaço tridimensional, suas propriedades, relações e medidas (áreas e volumes). É um ramo fundamental da matemática, com aplicações em engenharia, arquitetura e design, e frequentemente abordado em questões de vestibular da Vunesp.

## 8.1. Vistas Ortogonais e Representação Plana

As **vistas ortogonais** são projeções de um objeto tridimensional em planos perpendiculares entre si. Elas permitem representar um objeto espacial no plano 2D, mostrando suas dimensões e características a partir de diferentes pontos de vista (superior, frontal, lateral).
-   **Vista Frontal**: O que se vê olhando o objeto de frente.
-   **Vista Superior**: O que se vê olhando o objeto de cima.
-   **Vista Lateral**: O que se vê olhando o objeto de lado.

## 8.2. Poliedros e Corpos Redondos

### Poliedros

São sólidos geométricos cujas superfícies são formadas por polígonos planos (faces). Não possuem curvas.
-   **Faces**: Os polígonos que formam a superfície.
-   **Arestas**: As intersecções das faces.
-   **Vértices**: Os pontos de encontro das arestas.
-   **Relação de Euler**: Para qualquer poliedro convexo, $V - A + F = 2$ (Vértices - Arestas + Faces = 2).
-   **Poliedros de Platão**: Poliedros regulares convexos (tetraedro, cubo, octaedro, dodecaedro, icosaedro).

### Corpos Redondos

São sólidos geométricos que possuem pelo menos uma superfície curva. São gerados pela rotação de uma figura plana.
-   **Cilindro**: Gerado pela rotação de um retângulo em torno de um de seus lados.
-   **Cone**: Gerado pela rotação de um triângulo retângulo em torno de um de seus catetos.
-   **Esfera**: Gerada pela rotação de um semicírculo em torno de seu diâmetro.

## 8.3. Prisma, Pirâmides e Respectivos Troncos (Áreas, Volumes e Capacidade)

### Prisma

Poliedro com duas bases paralelas e congruentes, e faces laterais que são paralelogramos.
-   **Volume**: $V = A_{base} \times h$ (Área da base $\times$ altura).
-   **Área Total**: $A_{total} = 2A_{base} + A_{lateral}$

### Pirâmide

Poliedro com uma base poligonal e faces laterais triangulares que se encontram em um ponto (vértice).
-   **Volume**: $V = \frac{1}{3} A_{base} \times h$
-   **Área Total**: $A_{total} = A_{base} + A_{lateral}$

### Tronco de Pirâmide / Tronco de Cone

Formado quando uma pirâmide ou cone é cortado por um plano paralelo à base. Possui duas bases semelhantes e paralelas.
-   **Volume de Tronco**: $V_{tronco} = \frac{h}{3} (A_B + \sqrt{A_B A_b} + A_b)$ (onde $A_B$ é a área da base maior, $A_b$ é a área da base menor e $h$ é a altura do tronco).

## 8.4. Cilindro, Cone e Esfera (Áreas, Volumes e Capacidade)

### Cilindro

-   **Volume**: $V = \pi r^2 h$ (Área da base $\times$ altura).
-   **Área Lateral**: $A_{lateral} = 2\pi r h$
-   **Área Total**: $A_{total} = 2A_{base} + A_{lateral} = 2\pi r^2 + 2\pi r h = 2\pi r(r+h)$

### Cone

-   **Volume**: $V = \frac{1}{3} \pi r^2 h$
-   **Área Lateral**: $A_{lateral} = \pi r g$ (onde $g$ é a geratriz, $g^2 = r^2 + h^2$)
-   **Área Total**: $A_{total} = A_{base} + A_{lateral} = \pi r^2 + \pi r g = \pi r(r+g)$

### Esfera

-   **Volume**: $V = \frac{4}{3} \pi r^3$
-   **Área da Superfície**: $A_{superficie} = 4\pi r^2$

### Capacidade

Relacionada ao volume. $1 \text{ m}^3 = 1000 \text{ litros}$, $1 \text{ dm}^3 = 1 \text{ litro}$, $1 \text{ cm}^3 = 1 \text{ mL}$.

## 8.5. Deformações de Áreas e Ângulos Provocadas pelas Diferentes Projeções Usadas na Cartografia

As projeções cartográficas são formas de representar a superfície curva da Terra em um plano, o que sempre gera deformações. Essas deformações podem afetar áreas, formas (ângulos) e distâncias.
-   **Projeções Conformes**: Preservam os ângulos (formas), mas distorcem as áreas. Ex: Projeção de Mercator.
-   **Projeções Equivalentes (ou Autálicas)**: Preservam as áreas, mas distorcem as formas (ângulos). Ex: Projeção de Gall-Peters.
-   **Projeções Equidistantes**: Preservam algumas distâncias (geralmente a partir de um ponto ou ao longo de certas linhas), mas não todas.

É impossível ter uma projeção que preserve todas essas propriedades simultaneamente. A escolha da projeção depende do propósito do mapa.

---

## Exercícios Estilo Vunesp

**Questão 1 (Vunesp Adaptada):**
Um cilindro circular reto tem raio da base de 3 cm e altura de 10 cm. Qual é o volume desse cilindro? (Use $\pi \approx 3.14$)

a) $30$ cm³
b) $60$ cm³
c) $90$ cm³
d) $282.6$ cm³
e) $942$ cm³

**Resolução:**
A fórmula do volume do cilindro é $V = \pi r^2 h$.
Dados: $r = 3$ cm, $h = 10$ cm, $\pi \approx 3.14$.
$V = 3.14 \times (3^2) \times 10$
$V = 3.14 \times 9 \times 10$
$V = 3.14 \times 90$
$V = 282.6$ cm³

**Alternativa Correta: d)**

---

**Questão 2 (Vunesp Adaptada):**
Para um poliedro convexo, sabe-se que ele possui 6 vértices e 12 arestas. Quantas faces esse poliedro possui?

a) 6
b) 8
c) 10
d) 12
e) 14

**Resolução:**
Utilizamos a Relação de Euler para poliedros convexos: $V - A + F = 2$.
Dados: Vértices ($V$) = 6, Arestas ($A$) = 12.
$6 - 12 + F = 2$
$-6 + F = 2$
$F = 2 + 6$
$F = 8$
O poliedro possui 8 faces.

**Alternativa Correta: b)**
