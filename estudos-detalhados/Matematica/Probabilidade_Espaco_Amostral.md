# Probabilidade: Espaço Amostral e Conceituação

A probabilidade é um ramo da matemática que estuda a chance de um evento ocorrer. Para entendê-la, é fundamental compreender os conceitos de experimento aleatório, espaço amostral e evento.

## Experimento Aleatório
Um experimento aleatório é qualquer processo cujo resultado não pode ser previsto com certeza, mesmo que seja repetido sob as mesmas condições. No entanto, todos os resultados possíveis são conhecidos.

**Exemplos:**
*   Lançar um dado e observar a face superior.
*   Lançar uma moeda e observar a face voltada para cima.
*   Retirar uma carta de um baralho e observar seu naipe.

## Espaço Amostral (Ω ou S)
O espaço amostral é o conjunto de todos os resultados possíveis de um experimento aleatório. Ele pode ser discreto (finito ou infinito contável) ou contínuo (infinito não contável).

**Espaço Amostral Discreto:**
*   **Finito:** Quando o número de resultados é limitado.
    *   Lançamento de um dado: Ω = {1, 2, 3, 4, 5, 6}
    *   Lançamento de uma moeda: Ω = {Cara, Coroa}
*   **Infinito Contável:** Quando os resultados podem ser colocados em correspondência com os números naturais.
    *   Número de lançamentos de uma moeda até obter a primeira cara: Ω = {1, 2, 3, ...}

**Espaço Amostral Contínuo:**
*   Quando os resultados podem assumir qualquer valor dentro de um intervalo real.
    *   Tempo de vida de uma lâmpada em horas: Ω = [0, ∞)
    *   Altura de uma pessoa em cm: Ω = [150, 200] (se considerarmos um intervalo)

## Evento (E)
Um evento é qualquer subconjunto do espaço amostral. Ele representa um ou mais resultados específicos de um experimento aleatório.

**Exemplos:**
*   No lançamento de um dado, o evento "sair um número par": E = {2, 4, 6}
*   No lançamento de uma moeda, o evento "sair cara": E = {Cara}

## Conceituação de Probabilidade (Clássica)
A probabilidade clássica de um evento (E) ocorrer é dada pela razão entre o número de casos favoráveis ao evento e o número total de casos possíveis no espaço amostral, assumindo que todos os resultados são igualmente prováveis (eventos equiprováveis).

Fórmula: $$P(E) = \frac{\text{Número de casos favoráveis ao evento}}{\text{Número total de casos possíveis no espaço amostral}}$$

**Exemplos:**
*   Probabilidade de sair um número par no lançamento de um dado:
    *   Casos favoráveis = {2, 4, 6} -> 3
    *   Espaço amostral = {1, 2, 3, 4, 5, 6} -> 6
    *   P(par) = 3/6 = 1/2 = 0.5 ou 50%

*   Probabilidade de sair cara no lançamento de uma moeda:
    *   Casos favoráveis = {Cara} -> 1
    *   Espaço amostral = {Cara, Coroa} -> 2
    *   P(cara) = 1/2 = 0.5 ou 50%

## Exercícios Estilo Vunesp

**Exercício 1 (VUNESP - Adaptado)**

No lançamento de um dado comum e honesto, qual a probabilidade de o número obtido na face superior ser um divisor de 6?

A) 1/6
B) 1/3
C) 1/2
D) 2/3
E) 5/6

**Resolução:**
*   Espaço amostral (Ω) = {1, 2, 3, 4, 5, 6}. Total de casos possíveis = 6.
*   Divisores de 6: {1, 2, 3, 6}. Casos favoráveis = 4.
*   P(divisor de 6) = 4/6 = 2/3.

**Resposta:** D

---

**Exercício 2 (VUNESP - Adaptado)**

Uma urna contém 10 bolas idênticas, numeradas de 1 a 10. Ao retirar uma bola aleatoriamente, qual a probabilidade de o número da bola ser primo?

A) 2/10
B) 3/10
C) 4/10
D) 5/10
E) 6/10

**Resolução:**
*   Espaço amostral (Ω) = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}. Total de casos possíveis = 10.
*   Números primos entre 1 e 10: {2, 3, 5, 7}. Casos favoráveis = 4.
*   P(número primo) = 4/10.

**Resposta:** C
