# Probabilidade: Probabilidade Condicional e Eventos Independentes

Nesta seção, exploraremos dois conceitos cruciais em probabilidade: a probabilidade condicional, que lida com a probabilidade de um evento ocorrer dado que outro já ocorreu, e eventos independentes, onde a ocorrência de um não afeta a probabilidade do outro.

## Probabilidade Condicional (P(A|B))

A **probabilidade condicional** de um evento A ocorrer, dado que um evento B já ocorreu (e P(B) > 0), é denotada por P(A|B) e é calculada pela fórmula:

Fórmula: $$P(A|B) = \frac{P(A \cap B)}{P(B)}$$

Onde:
*   P(A|B) é a probabilidade de A, dado B.
*   P(A ∩ B) é a probabilidade da intersecção de A e B (ambos ocorrerem).
*   P(B) é a probabilidade de B ocorrer.

**Exemplo:**
*   Em um grupo de 100 pessoas, 40 são estudantes (E) e 20 usam óculos (O). Dentre os estudantes, 15 usam óculos. Qual a probabilidade de uma pessoa usar óculos, sabendo que ela é estudante?
    *   P(O ∩ E) = 15/100 (15 pessoas são estudantes E usam óculos)
    *   P(E) = 40/100 (40 pessoas são estudantes)
    *   P(O|E) = P(O ∩ E) / P(E) = (15/100) / (40/100) = 15/40 = 3/8

## Eventos Independentes

Dois eventos A e B são **independentes** se a ocorrência de um não altera a probabilidade de ocorrência do outro. Isso significa que:

*   P(A|B) = P(A) (a probabilidade de A não é afetada por B)
*   P(B|A) = P(B) (a probabilidade de B não é afetada por A)

Se A e B são eventos independentes, a probabilidade da intersecção é o produto das probabilidades individuais:

Fórmula: $$P(A \cap B) = P(A) \cdot P(B)$$

**Exemplo:**
*   Qual a probabilidade de lançar uma moeda e obter "Cara" e, em seguida, lançar um dado e obter "6"?
    *   Evento A: Obter Cara na moeda. P(A) = 1/2.
    *   Evento B: Obter 6 no dado. P(B) = 1/6.
    *   Os eventos são independentes, pois o resultado da moeda não afeta o resultado do dado.
    *   P(A ∩ B) = P(A) * P(B) = (1/2) * (1/6) = 1/12

**Teste de Independência:** Para verificar se dois eventos são independentes, basta checar se P(A ∩ B) = P(A) * P(B).

## Exercícios Estilo Vunesp

**Exercício 1 (VUNESP - Adaptado)**

Em uma pesquisa, verificou-se que 60% dos entrevistados leem jornais (J) e 30% leem revistas (R). Sabendo-se que 20% leem ambos (jornais e revistas), qual a probabilidade de um entrevistado ler revistas, dado que ele lê jornais?

A) 1/3

B) 1/2

C) 2/3

D) 1/4

E) 2/5

**Resolução:**
*   P(J) = 0.60
*   P(R) = 0.30
*   P(J ∩ R) = 0.20
*   P(R|J) = P(J ∩ R) / P(J) = 0.20 / 0.60 = 2/6 = 1/3.

**Resposta:** A

---

**Exercício 2 (VUNESP - Adaptado)**

Duas máquinas, M1 e M2, operam de forma independente. A probabilidade de a máquina M1 falhar em um dia é de 0,1, e a probabilidade de a máquina M2 falhar no mesmo dia é de 0,05. Qual a probabilidade de ambas as máquinas falharem em um determinado dia?

A) 0,15

B) 0,05

C) 0,005

D) 0,145

E) 0,25

**Resolução:**
*   P(M1 falhar) = 0.1
*   P(M2 falhar) = 0.05
*   Como são eventos independentes, P(M1 e M2 falharem) = P(M1 falhar) * P(M2 falhar).
*   P(M1 ∩ M2) = 0.1 * 0.05 = 0.005.

**Resposta:** C
