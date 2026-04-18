# Matemática: Conjuntos Numéricos, Notação Científica e Noção de Erro em Medições

## Conjuntos Numéricos

Os conjuntos numéricos são classificações de números com propriedades específicas.

1.  **Números Naturais ($\mathbb{N}$):** $\{0, 1, 2, 3, ...\}$ - Usados para contagem.
2.  **Números Inteiros ($\mathbb{Z}$):** $\{..., -2, -1, 0, 1, 2, ...\}$ - Inclui os naturais e seus opostos negativos.
3.  **Números Racionais ($\mathbb{Q}$):** Números que podem ser expressos como fração $a/b$, onde $a \in \mathbb{Z}$ e $b \in \mathbb{Z}, b \neq 0$. Inclui decimais exatos e dízimas periódicas. Ex: $0.5 = 1/2$, $0.333... = 1/3$.
4.  **Números Irracionais ($\mathbb{I}$):** Números que não podem ser expressos como fração e possuem infinitas casas decimais não-periódicas. Ex: $\sqrt{2}$, $\pi$.
5.  **Números Reais ($\mathbb{R}$):** União dos números racionais e irracionais ($\mathbb{Q} \cup \mathbb{I}$). Praticamente todos os números que usamos no dia a dia.

### Operações e Propriedades
- **Adição e Subtração:** Mantêm a natureza do conjunto (exceções: $\mathbb{N}$ para subtração de menores por maiores).
- **Multiplicação e Divisão:** Mantêm a natureza do conjunto (exceções: divisão por zero é indefinida).
- **Ordem:** Números podem ser comparados (maior, menor, igual).
- **Reta Numérica:** Representação visual dos números reais.

## Notação Científica

Usada para expressar números muito grandes ou muito pequenos de forma concisa. Formato: $a \times 10^b$, onde $1 \le |a| < 10$ e $b$ é um número inteiro.

**Exemplo:**
- 300.000.000 m/s = $3 \times 10^8$ m/s
- 0,0000000001 m = $1 \times 10^{-10}$ m

## Algarismos Significativos e Noção de Erro em Medições

**Algarismos Significativos:** Dígitos que contribuem para a precisão de uma medida.
- Dígitos não-zero são sempre significativos.
- Zeros entre dígitos não-zero são significativos.
- Zeros à esquerda (antes do primeiro dígito não-zero) não são significativos.
- Zeros à direita de um dígito não-zero são significativos se houver um ponto decimal.

**Noção de Erro em Medições:** Toda medição possui uma incerteza.
- **Erro Absoluto:** Diferença entre o valor medido e o valor real (ou aceito).
- **Erro Relativo:** Erro absoluto dividido pelo valor real, muitas vezes expresso em porcentagem.
- **Precisão:** Grau de concordância entre medidas repetidas.
- **Exatidão:** Grau de proximidade de uma medida ao valor real.

---

## Exercícios Estilo Vunesp

### Exercício 1 (Conjuntos Numéricos)

Considere os números: $\sqrt{3}$, $1/2$, $-5$, $0,333...$, $2\pi$.
Assinale a alternativa que classifica corretamente cada número em relação aos conjuntos numéricos.

a) $\sqrt{3} \in \mathbb{Q}$; $1/2 \in \mathbb{Z}$; $-5 \in \mathbb{N}$; $0,333... \in \mathbb{I}$; $2\pi \in \mathbb{R}$.
b) $\sqrt{3} \in \mathbb{I}$; $1/2 \in \mathbb{Q}$; $-5 \in \mathbb{Z}$; $0,333... \in \mathbb{Q}$; $2\pi \in \mathbb{I}$.
c) $\sqrt{3} \in \mathbb{R}$; $1/2 \in \mathbb{I}$; $-5 \in \mathbb{Q}$; $0,333... \in \mathbb{N}$; $2\pi \in \mathbb{Z}$.
d) $\sqrt{3} \in \mathbb{Z}$; $1/2 \in \mathbb{N}$; $-5 \in \mathbb{R}$; $0,333... \in \mathbb{I}$; $2\pi \in \mathbb{Q}$.
e) $\sqrt{3} \in \mathbb{Q}$; $1/2 \in \mathbb{R}$; $-5 \in \mathbb{I}$; $0,333... \in \mathbb{Z}$; $2\pi \in \mathbb{N}$.

**Resposta Correta:** b)
- $\sqrt{3}$ é um número irracional ($\mathbb{I}$).
- $1/2$ é um número racional ($\mathbb{Q}$).
- $-5$ é um número inteiro ($\mathbb{Z}$).
- $0,333...$ é uma dízima periódica, portanto, um número racional ($\mathbb{Q}$).
- $2\pi$ é um número irracional ($\mathbb{I}$) (já que $\pi$ é irracional, $2\pi$ também é).

### Exercício 2 (Notação Científica e Algarismos Significativos)

Um pesquisador mediu o comprimento de um objeto e obteve o valor de 0,00000000520 metros.

1.  Qual a representação desse valor em notação científica?
2.  Quantos algarismos significativos possui essa medida?

a) $5,2 \times 10^{-9}$ m; 2 algarismos significativos.
b) $5,20 \times 10^{-9}$ m; 3 algarismos significativos.
c) $5,20 \times 10^9$ m; 3 algarismos significativos.
d) $5,2 \times 10^{-9}$ m; 3 algarismos significativos.
e) $5,200 \times 10^{-9}$ m; 4 algarismos significativos.

**Resposta Correta:** b)
1.  Para converter 0,00000000520 para notação científica, movemos a vírgula 9 casas para a direita, resultando em $5,20$. Como movemos para a direita, o expoente é negativo: $10^{-9}$. Assim, $5,20 \times 10^{-9}$ m.
2.  Os zeros à esquerda (0,000...) não são significativos. Os dígitos 5 e 2 são significativos. O zero à direita (o último 0) é significativo porque está após um dígito não-zero e há um ponto decimal implícito na representação original, indicando que a precisão foi até aquela casa. Portanto, são 3 algarismos significativos (5, 2 e o último 0).
