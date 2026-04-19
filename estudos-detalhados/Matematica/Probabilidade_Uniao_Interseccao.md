# Probabilidade: Eventos Mutuamente Exclusivos, União e Intersecção

Continuando nosso estudo de probabilidade, vamos aprofundar nos conceitos de eventos mutuamente exclusivos, e como calcular a probabilidade da união e intersecção de eventos.

## Eventos Mutuamente Exclusivos

Dois eventos são **mutuamente exclusivos** (ou disjuntos) se a ocorrência de um impede a ocorrência do outro, ou seja, eles não podem ocorrer ao mesmo tempo. Em termos de conjuntos, a intersecção entre eles é vazia (E₁ ∩ E₂ = ∅).

**Exemplo:**
*   No lançamento de um dado, o evento E₁: "sair um número par" ({2, 4, 6}) e o evento E₂: "sair um número ímpar" ({1, 3, 5}) são mutuamente exclusivos, pois um número não pode ser par e ímpar ao mesmo tempo.
*   No lançamento de um dado, o evento E₁: "sair um número menor que 2" ({1}) e o evento E₂: "sair o número 4" ({4}) são mutuamente exclusivos.

**Exemplo de eventos NÃO mutuamente exclusivos:**
*   No lançamento de um dado, o evento E₁: "sair um número par" ({2, 4, 6}) e o evento E₃: "sair um número menor que 4" ({1, 2, 3}) NÃO são mutuamente exclusivos, pois o número 2 pertence a ambos os eventos.

## Probabilidade da União de Eventos (P(E₁ ∪ E₂))

A probabilidade da união de dois eventos E₁ e E₂ (ou seja, a probabilidade de E₁ ocorrer OU E₂ ocorrer) depende se eles são mutuamente exclusivos ou não.

### 1. Para Eventos Mutuamente Exclusivos
Se E₁ e E₂ são mutuamente exclusivos, a probabilidade de E₁ ou E₂ ocorrer é a soma das probabilidades de cada evento, pois não há resultados em comum.

Fórmula: $$P(E_1 \cup E_2) = P(E_1) + P(E_2)$$

**Exemplo:**
*   No lançamento de um dado, qual a probabilidade de sair um número par OU um número ímpar?
    *   P(par) = 3/6 = 1/2
    *   P(ímpar) = 3/6 = 1/2
    *   P(par ou ímpar) = P(par) + P(ímpar) = 1/2 + 1/2 = 1 = 100%

### 2. Para Eventos NÃO Mutuamente Exclusivos
Se E₁ e E₂ NÃO são mutuamente exclusivos, a probabilidade da união é a soma das probabilidades individuais menos a probabilidade da intersecção (P(E₁ ∩ E₂)), para evitar contar duas vezes os resultados em comum.

Fórmula: $$P(E_1 \cup E_2) = P(E_1) + P(E_2) - P(E_1 \cap E_2)$$

**Exemplo:**
*   No lançamento de um dado, qual a probabilidade de sair um número par OU um número menor que 4?
    *   E₁ (par) = {2, 4, 6} -> P(E₁) = 3/6
    *   E₂ (menor que 4) = {1, 2, 3} -> P(E₂) = 3/6
    *   E₁ ∩ E₂ (par E menor que 4) = {2} -> P(E₁ ∩ E₂) = 1/6
    *   P(E₁ ∪ E₂) = 3/6 + 3/6 - 1/6 = 5/6

## Probabilidade da Intersecção de Eventos (P(E₁ ∩ E₂))

A probabilidade da intersecção de dois eventos E₁ e E₂ (ou seja, a probabilidade de E₁ ocorrer E E₂ ocorrer) depende se eles são eventos independentes ou não. Para este tópico, focaremos em eventos dentro de um mesmo experimento (não independentes, que veremos no próximo tópico).

Para eventos que ocorrem em um único experimento ou quando um afeta o outro, a probabilidade da intersecção é diretamente o número de elementos em comum dividido pelo total do espaço amostral.

Fórmula: $$P(E_1 \cap E_2) = \frac{\text{Número de resultados em } E_1 \cap E_2}{\text{Número total de resultados em } \Omega}$$

**Exemplo:**
*   Em um baralho de 52 cartas, qual a probabilidade de retirar uma carta que seja "Rei" E "de copas"?
    *   E₁ (Rei) = 4 reis
    *   E₂ (Copas) = 13 cartas de copas
    *   E₁ ∩ E₂ (Rei E de copas) = {Rei de copas} -> 1 carta
    *   P(Rei e Copas) = 1/52

## Exercícios Estilo Vunesp

**Exercício 1 (VUNESP - Adaptado)**

Em uma caixa, há 5 bolas azuis e 3 bolas vermelhas. Se uma bola é retirada ao acaso, qual a probabilidade de ela ser azul ou vermelha?

A) 3/8

B) 5/8

C) 1/8

D) 8/8

E) 0/8

**Resolução:**
*   Espaço amostral total = 5 azuis + 3 vermelhas = 8 bolas.
*   Evento A: Retirar bola azul. P(A) = 5/8.
*   Evento V: Retirar bola vermelha. P(V) = 3/8.
*   Os eventos A e V são mutuamente exclusivos (a bola não pode ser azul e vermelha ao mesmo tempo).
*   P(A ou V) = P(A) + P(V) = 5/8 + 3/8 = 8/8 = 1.

**Resposta:** D

---

**Exercício 2 (VUNESP - Adaptado)**

Em uma classe de 30 alunos, 18 gostam de Matemática, 10 gostam de Português e 5 gostam de ambas as matérias. Ao escolher um aluno ao acaso, qual a probabilidade de ele gostar de Matemática ou de Português?

A) 23/30

B) 25/30

C) 28/30

D) 20/30

E) 15/30

**Resolução:**
*   Total de alunos = 30.
*   Gostam de Matemática (M): P(M) = 18/30.
*   Gostam de Português (P): P(P) = 10/30.
*   Gostam de ambas (M e P): P(M ∩ P) = 5/30.
*   Os eventos M e P NÃO são mutuamente exclusivos.
*   P(M ou P) = P(M) + P(P) - P(M ∩ P) = 18/30 + 10/30 - 5/30 = 23/30.

**Resposta:** A
