# Sistemas de Contagem e de Medidas <span class="tag-media-frequencia">[⚠️ FREQUÊNCIA MÉDIA]</span>

Os sistemas de contagem e de medidas são a base para quantificar e comparar grandezas no dia a dia e na ciência. O domínio do Sistema Internacional de Medidas (SI) e a compreensão de diferentes bases numéricas são essenciais para a resolução de problemas em diversas áreas do conhecimento e em vestibulares como o da Vunesp.

## 10.1. Sistema Internacional de Medidas (SI)

O **Sistema Internacional de Unidades (SI)** é o sistema de unidades de medida mais amplamente utilizado no mundo, padronizando as unidades para facilitar a comunicação e o intercâmbio científico e comercial.

**Grandezas de Base do SI (as 7 fundamentais):**
-   **Comprimento**: metro (m)
-   **Massa**: quilograma (kg)
-   **Tempo**: segundo (s)
-   **Corrente Elétrica**: ampère (A)
-   **Temperatura Termodinâmica**: kelvin (K)
-   **Quantidade de Matéria**: mol (mol)
-   **Intensidade Luminosa**: candela (cd)

**Prefixos do SI:**
São usados para formar múltiplos e submúltiplos das unidades, facilitando a representação de valores muito grandes ou muito pequenos.
-   **Quilo (k)**: $10^3$ (ex: 1 km = 1000 m)
-   **Hecto (h)**: $10^2$
-   **Deca (da)**: $10^1$
-   **Deci (d)**: $10^{-1}$
-   **Centi (c)**: $10^{-2}$ (ex: 1 cm = 0.01 m)
-   **Mili (m)**: $10^{-3}$ (ex: 1 mm = 0.001 m)
-   **Micro ($\mu$)**: $10^{-6}$
-   **Nano (n)**: $10^{-9}$
-   **Giga (G)**: $10^9$
-   **Mega (M)**: $10^6$

**Conversão de Unidades:**
É crucial saber converter entre diferentes unidades, especialmente aquelas de área (m² para cm²) e volume (m³ para litros).
-   $1 \text{ m}^2 = 100 \text{ dm}^2 = 10.000 \text{ cm}^2$
-   $1 \text{ m}^3 = 1.000 \text{ dm}^3 = 1.000.000 \text{ cm}^3$
-   $1 \text{ dm}^3 = 1 \text{ litro}$
-   $1 \text{ cm}^3 = 1 \text{ mL}$

## 10.2. Base Decimal, Base Binária, Base Sexagesimal e Outras Bases de Sistemas de Contagem

Um **sistema de numeração** é um conjunto de símbolos e regras que permite representar números. A "base" de um sistema indica quantos algarismos diferentes são utilizados para representar os números.

### Base Decimal (Base 10)

É o sistema de numeração que usamos no dia a dia. Utiliza 10 algarismos (0, 1, 2, 3, 4, 5, 6, 7, 8, 9). Cada posição de um algarismo em um número representa uma potência de 10.
*Exemplo*: $123_{10} = 1 \times 10^2 + 2 \times 10^1 + 3 \times 10^0$

### Base Binária (Base 2)

Utiliza apenas 2 algarismos (0 e 1). É a base fundamental para a computação digital, onde 0 representa "desligado" e 1 representa "ligado". Cada posição representa uma potência de 2.
*Exemplo*: Converter $1101_2$ para base decimal:
$1101_2 = 1 \times 2^3 + 1 \times 2^2 + 0 \times 2^1 + 1 \times 2^0$
$1101_2 = 1 \times 8 + 1 \times 4 + 0 \times 2 + 1 \times 1$
$1101_2 = 8 + 4 + 0 + 1 = 13_{10}$

### Base Sexagesimal (Base 60)

Utiliza 60 como base. É usada para medir tempo (minutos e segundos) e ângulos (graus, minutos e segundos). Origem babilônica.
*Exemplo*: 1 hora = 60 minutos; 1 minuto = 60 segundos. 1 grau = 60 minutos; 1 minuto = 60 segundos.

### Outras Bases de Sistemas de Contagem

Qualquer número inteiro maior que 1 pode ser uma base. Por exemplo:
-   **Base Octal (Base 8)**: Utiliza algarismos de 0 a 7. 
    *Exemplo*: $25_8 = 2 \times 8^1 + 5 \times 8^0 = 16 + 5 = 21_{10}$
-   **Base Hexadecimal (Base 16)**: Utiliza algarismos de 0 a 9 e as letras A a F para representar 10 a 15. Muito usada em computação. 
    *Exemplo*: $1A_{16} = 1 \times 16^1 + 10 \times 16^0 = 16 + 10 = 26_{10}$

**Conversão entre Bases:**
-   **De qualquer base para a decimal**: Multiplicar cada algarismo pela base elevada à potência da posição correspondente e somar os resultados (como nos exemplos acima).
-   **De decimal para qualquer base**: Dividir o número decimal pela base sucessivamente e coletar os restos da divisão do último ao primeiro.

---

## Exercícios Estilo Vunesp

**Questão 1 (Vunesp Adaptada):**
Uma caixa d'água tem o formato de um paralelepípedo reto-retângulo com as seguintes dimensões internas: 2 metros de comprimento, 1,5 metros de largura e 1 metro de altura. Qual a capacidade total dessa caixa d'água em litros?

a) 30 litros
b) 300 litros
c) 3.000 litros
d) 30.000 litros
e) 300.000 litros

**Resolução:**
Primeiro, calculamos o volume da caixa d'água em metros cúbicos:
$V = comprimento \times largura \times altura$
$V = 2 \text{ m} \times 1.5 \text{ m} \times 1 \text{ m} = 3 \text{ m}^3$

Sabemos que $1 \text{ m}^3 = 1.000 \text{ litros}$.
Então, a capacidade em litros é:
Capacidade = $3 \text{ m}^3 \times 1.000 \text{ litros/m}^3 = 3.000 \text{ litros}$.

**Alternativa Correta: c)**

---

**Questão 2 (Vunesp Adaptada):**
O número binário $1011_2$ corresponde a qual número na base decimal?

a) 9
b) 10
c) 11
d) 12
e) 13

**Resolução:**
Para converter um número binário para decimal, multiplicamos cada algarismo pela potência de 2 correspondente à sua posição, da direita para a esquerda, começando com $2^0$.
$1011_2 = (1 \times 2^3) + (0 \times 2^2) + (1 \times 2^1) + (1 \times 2^0)$
$1011_2 = (1 \times 8) + (0 \times 4) + (1 \times 2) + (1 \times 1)$
$1011_2 = 8 + 0 + 2 + 1$
$1011_2 = 11_{10}$

**Alternativa Correta: c)**
