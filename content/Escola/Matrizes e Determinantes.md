Tags: [[Matemática]] [[Álgebra Linear]] [[Matrizes e Determinantes]]

> [!abstract]
> Matrizes são estruturas retangulares de números organizados em linhas e colunas, amplamente utilizadas para representar e resolver problemas que envolvem múltiplas variáveis simultaneamente, desde **sistemas de equações lineares** até transformações geométricas em computação gráfica. A cada matriz quadrada é possível associar um número real, o **determinante**, que sintetiza propriedades essenciais da matriz — em particular, sua capacidade de ser invertida. As operações fundamentais entre matrizes (adição, multiplicação por escalar e multiplicação entre matrizes) seguem regras próprias, distintas da álgebra numérica convencional, sobretudo no caso da multiplicação, que **não é comutativa**. O estudo conjunto de matrizes e determinantes culmina na resolução de **sistemas lineares** por métodos como a Regra de Cramer, tornando esse conteúdo uma ferramenta central tanto para a Matemática pura quanto para aplicações em Física, Economia e Ciência da Computação.

## 1. Definição e Notação de Matrizes

- Uma **matriz** é uma tabela retangular de números (reais, em geral, no contexto do Ensino Médio), organizada em **linhas** e **colunas**.
- Uma matriz de **ordem $m \times n$** possui $m$ linhas e $n$ colunas; cada elemento é identificado por dois índices, $a_{ij}$, onde $i$ indica a linha e $j$ a coluna em que o elemento se encontra.
- Notação geral:
$$A = \begin{pmatrix} a_{11} & a_{12} & \cdots & a_{1n} \\ a_{21} & a_{22} & \cdots & a_{2n} \\ \vdots & \vdots & \ddots & \vdots \\ a_{m1} & a_{m2} & \cdots & a_{mn} \end{pmatrix}$$

## 2. Tipos Especiais de Matrizes

- **Matriz quadrada:** possui o mesmo número de linhas e colunas ($m = n$); apenas matrizes quadradas possuem determinante e podem ser invertidas.
- **Matriz nula:** todos os elementos são iguais a zero.
- **Matriz identidade ($I$):** matriz quadrada em que todos os elementos da diagonal principal são iguais a 1, e todos os demais são iguais a 0; funciona como o "elemento neutro" da multiplicação de matrizes.
- **Matriz diagonal:** matriz quadrada em que todos os elementos fora da diagonal principal são nulos.
- **Matriz transposta ($A^T$):** obtida trocando-se, ordenadamente, as linhas pelas colunas da matriz original.
- **Matriz simétrica:** matriz quadrada que é igual à sua própria transposta ($A = A^T$).

## 3. Adição, Subtração e Multiplicação por Escalar

- **Adição e subtração:** só são possíveis entre matrizes de **mesma ordem**, somando (ou subtraindo) os elementos correspondentes de mesma posição:
$$(A \pm B)_{ij} = a_{ij} \pm b_{ij}$$
- **Multiplicação por escalar:** multiplica-se cada elemento da matriz pelo número (escalar) $k$:
$$(k \cdot A)_{ij} = k \cdot a_{ij}$$

## 4. Multiplicação de Matrizes

- A multiplicação $A \cdot B$ só é possível quando o **número de colunas de $A$** é igual ao **número de linhas de $B$**. Se $A$ tem ordem $m \times n$ e $B$ tem ordem $n \times p$, o produto $A \cdot B$ terá ordem $m \times p$.
- Cada elemento do produto é obtido pela soma dos produtos dos elementos correspondentes da linha de $A$ pela coluna de $B$:
$$(A \cdot B)_{ij} = \sum_{k=1}^{n} a_{ik} \cdot b_{kj}$$
- **A multiplicação de matrizes não é comutativa**: em geral, $A \cdot B \neq B \cdot A$, e o produto $B \cdot A$ pode nem sequer existir, dependendo das ordens envolvidas.

## 5. Matriz Inversa

- A **matriz inversa** de uma matriz quadrada $A$, quando existe, é a matriz $A^{-1}$ tal que:
$$A \cdot A^{-1} = A^{-1} \cdot A = I$$
- Uma matriz quadrada só possui inversa se, e somente se, seu **determinante for diferente de zero** — matrizes com determinante igual a zero são chamadas de **matrizes singulares** e não possuem inversa.

## 6. Determinantes: Definição e Cálculo

- O **determinante** é um número real associado a toda matriz quadrada, que sintetiza informações importantes sobre ela, como a existência de matriz inversa e a interpretação geométrica de área/volume associada às suas linhas ou colunas.
- **Determinante de matriz $2 \times 2$:**
$$\det\begin{pmatrix} a & b \\ c & d \end{pmatrix} = a \cdot d - b \cdot c$$
- **Regra de Sarrus** (exclusiva para matrizes $3 \times 3$): repetem-se as duas primeiras colunas à direita da matriz, somam-se os produtos das três diagonais "descendentes" e subtraem-se os produtos das três diagonais "ascendentes".
- **Teorema de Laplace:** método geral, válido para matrizes de qualquer ordem, que calcula o determinante por meio da expansão em cofatores ao longo de uma linha ou coluna escolhida, reduzindo o cálculo a determinantes de matrizes menores (menores complementares).

## 7. Propriedades dos Determinantes

- Se uma matriz possui uma **linha ou coluna inteira de zeros**, seu determinante é igual a **zero**.
- Se uma matriz possui **duas linhas (ou colunas) iguais ou proporcionais**, seu determinante é igual a **zero**.
- **Trocar a posição de duas linhas** (ou colunas) de uma matriz **inverte o sinal** do determinante.
- O determinante da matriz **transposta** é igual ao determinante da matriz original: $\det(A) = \det(A^T)$.
- O determinante de um **produto de matrizes** é igual ao produto de seus determinantes: $\det(A \cdot B) = \det(A) \cdot \det(B)$.

## 8. Aplicação: Sistemas Lineares e a Regra de Cramer

- Um sistema de equações lineares pode ser representado na forma matricial $A \cdot X = B$, onde $A$ é a matriz dos coeficientes, $X$ é a matriz das incógnitas e $B$ é a matriz dos termos independentes.
- A **Regra de Cramer** permite resolver esse sistema, desde que $\det(A) \neq 0$, calculando cada incógnita como a razão entre dois determinantes:
$$x_i = \frac{\det(A_i)}{\det(A)}$$
 onde $A_i$ é a matriz obtida substituindo-se a coluna $i$ de $A$ pela coluna de termos independentes $B$.
- Se $\det(A) = 0$, o sistema **não pode ser resolvido pela Regra de Cramer** — ele será, nesse caso, **impossível** (sem solução) ou **indeterminado** (infinitas soluções), a depender da análise complementar dos determinantes das incógnitas.

## 9. Matriz Comparativa: Métodos de Cálculo de Determinante

| Método | Ordem da matriz | Procedimento | Observação |
|---|---|---|---|
| **Fórmula direta** | $2 \times 2$ | $ad - bc$ | Caso mais simples, sem necessidade de método auxiliar |
| **Regra de Sarrus** | $3 \times 3$ (exclusivo) | Repetição das duas primeiras colunas; soma das diagonais principais menos soma das secundárias | Não é válido para matrizes de outras ordens |
| **Teorema de Laplace** | Qualquer ordem $n \times n$ | Expansão em cofatores ao longo de uma linha ou coluna, reduzindo a determinantes menores | Mais trabalhoso, porém universal |

> [!quote] Strategic Counterpoint
> * **Erros Clássicos:**
> - Assumir que a multiplicação de matrizes é **comutativa**, calculando $B \cdot A$ como se fosse igual a $A \cdot B$ — em álgebra matricial, a ordem dos fatores **altera o produto**, e um dos dois produtos pode nem existir.
> - Tentar aplicar a **Regra de Sarrus** a matrizes de ordem diferente de $3 \times 3$ — esse método é válido **exclusivamente** para matrizes quadradas de ordem 3; para outras ordens, é necessário usar o Teorema de Laplace ou outros métodos.
> - Achar que toda matriz quadrada possui inversa — a existência da inversa depende diretamente do determinante ser **diferente de zero**; uma matriz com determinante nulo é singular e não admite inversa.
>
> * **Distinção Crítica:**
> - **Matriz Singular** vs. **Matriz Não-Singular (Invertível):** uma matriz é dita singular quando seu determinante é igual a zero, o que implica a **inexistência de matriz inversa** e, no contexto de sistemas lineares, geralmente sinaliza um sistema impossível ou indeterminado. Uma matriz não-singular (determinante diferente de zero) sempre possui inversa e permite resolver o sistema associado de forma única, inclusive pela Regra de Cramer.
>
> * **Aplicação Prática:**
> - Matrizes e determinantes são a base matemática de **transformações lineares em computação gráfica** — rotação, escala, translação e projeção de objetos em telas e jogos 3D são todas representadas e combinadas por meio de multiplicação de matrizes, tornando esse conteúdo diretamente aplicável em áreas como desenvolvimento de jogos, visão computacional e computação gráfica em geral.

---

Tags: [[Matemática]] [[Álgebra Linear]] [[Matrizes e Determinantes]]
