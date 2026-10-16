Tags: [[Matemática]] [[Análise Combinatória]] [[Probabilidade]]

> [!abstract]
> A Análise Combinatória é a área da Matemática que ensina a **contar** o número de possibilidades de um fenômeno sem enumerá-las uma a uma, e a Probabilidade usa essa contagem para medir a **chance** de um evento ocorrer em situações de incerteza. As duas áreas se complementam: no modelo clássico, em que os resultados são **equiprováveis**, a probabilidade de um evento é a razão entre o número de casos favoráveis e o de casos possíveis, e ambos os números costumam ser obtidos com as ferramentas combinatórias. O núcleo da contagem é o **Princípio Fundamental da Contagem**, do qual derivam os **arranjos**, as **permutações** e as **combinações**, ampliados por técnicas como **inclusão-exclusão**, **contagem pelo complementar** e **estrelas e barras**. Na probabilidade, ao conceito básico somam-se a **probabilidade condicional**, a **independência de eventos**, a **lei da probabilidade total** e o **Teorema de Bayes**, que permitem revisar crenças diante de novas informações, além da **distribuição binomial**, da **probabilidade geométrica** e da **esperança matemática**, usadas para modelar repetições de experimentos e ganhos médios. O domínio do assunto depende menos de decorar fórmulas e mais de escolher a ferramenta certa a partir da leitura do enunciado.

## 1. Princípios Fundamentais de Contagem

- **Princípio Multiplicativo (PFC):** se uma tarefa é composta de $k$ etapas **sucessivas e independentes**, com $n_1, n_2, \dots, n_k$ possibilidades respectivamente, o total de formas de realizá-la é o produto:
$$N = n_1 \cdot n_2 \cdot \dots \cdot n_k$$
 Exemplo: uma senha de 4 dígitos numéricos tem $10 \cdot 10 \cdot 10 \cdot 10 = 10.000$ possibilidades.
- **Princípio Aditivo:** se uma tarefa pode ser feita por **um caminho ou outro**, mutuamente exclusivos, com $m$ e $n$ possibilidades, o total é $m + n$. Em linguagem de enunciado, o "e" costuma indicar multiplicação, e o "ou", adição.
- **Fatorial:** produto dos naturais de 1 até $n$, por definição, com $0! = 1$:
$$n! = n \cdot (n-1) \cdot (n-2) \cdot \dots \cdot 2 \cdot 1$$
- **Contagem pelo complementar:** quando é difícil contar diretamente os casos desejados, conta-se o total e subtrai-se o que **não** interessa:
$$N_{\text{desejado}} = N_{\text{total}} - N_{\text{indesejado}}$$
- **Princípio da Inclusão-Exclusão:** para contar a união de conjuntos sem repetir elementos comuns:
$$|A \cup B| = |A| + |B| - |A \cap B|$$
$$|A \cup B \cup C| = |A| + |B| + |C| - |A \cap B| - |A \cap C| - |B \cap C| + |A \cap B \cap C|$$

## 2. Arranjos

- No **arranjo simples**, escolhem-se $p$ elementos distintos entre $n$, e a **ordem importa**:
$$A_{n,p} = \frac{n!}{(n-p)!}$$
 Exemplo: o pódio de uma corrida com 10 atletas (1º, 2º e 3º lugares) tem $A_{10,3} = 10 \cdot 9 \cdot 8 = 720$ formas.
- No **arranjo com repetição**, o mesmo elemento pode ser usado mais de uma vez, e o resultado é simplesmente o PFC com $n$ opções em cada uma das $p$ posições:
$$n^p$$
 Exemplo: uma senha de 8 caracteres alfanuméricos (62 símbolos) admite $62^8$, cerca de 218 trilhões de possibilidades.

## 3. Permutações

- **Permutação simples:** é o arranjo de **todos** os $n$ elementos distintos, ou seja, o número de formas de ordená-los:
$$P_n = n!$$
 Exemplo: os anagramas de "LIVRO", com 5 letras distintas, são $5! = 120$.
- **Permutação com repetição:** quando alguns elementos são iguais, divide-se pelo fatorial de cada grupo de repetidos, para eliminar ordenações indistinguíveis:
$$P_n^{a,b,c} = \frac{n!}{a! \cdot b! \cdot c!}$$
 Exemplo: os anagramas de "ARARA" (3 A's e 2 R's) são $\dfrac{5!}{3! \cdot 2!} = 10$.
- **Permutação circular:** em arranjos sem posição inicial fixa (mesa redonda), rotações geram a mesma disposição, e o total é:
$$PC_n = (n-1)!$$
 Exemplo: 5 pessoas em uma mesa redonda podem se sentar de $4! = 24$ formas. Para **colares e pulseiras**, que também podem ser virados, o total é $(n-1)!/2$, com $n \geq 3$.
- **Permutação caótica (desarranjo):** número de formas de ordenar $n$ elementos de modo que **nenhum** fique na posição original (por exemplo, $n$ cartas em $n$ envelopes, todas no envelope errado):
$$D_n = n! \sum_{k=0}^{n} \frac{(-1)^k}{k!} \qquad \text{ou} \qquad D_n = (n-1)\left(D_{n-1} + D_{n-2}\right)$$
 Os primeiros valores são $D_2 = 1$, $D_3 = 2$, $D_4 = 9$ e $D_5 = 44$.

## 4. Combinações e Suas Propriedades

- Na **combinação simples**, escolhem-se $p$ elementos entre $n$ e a **ordem não importa**, de modo que cada grupo é contado uma só vez, o que equivale a dividir o arranjo por $p!$:
$$C_{n,p} = \binom{n}{p} = \frac{n!}{p! \cdot (n-p)!}$$
 Exemplos: uma comissão de 3 pessoas escolhidas entre 8 tem $\binom{8}{3} = 56$ formas; a Mega-Sena, que sorteia 6 dezenas entre 60, tem $\binom{60}{6} = 50.063.860$ combinações possíveis.
- **Propriedades fundamentais:**
 - **Complementares:** $\binom{n}{p} = \binom{n}{n-p}$, pois escolher quem entra é o mesmo que escolher quem fica de fora;
 - **Valores extremos:** $\binom{n}{0} = \binom{n}{n} = 1$ e $\binom{n}{1} = n$;
 - **Relação de Stifel:** $\binom{n}{p} + \binom{n}{p+1} = \binom{n+1}{p+1}$;
 - **Número de subconjuntos:** um conjunto com $n$ elementos tem $2^n$ subconjuntos, pois $\sum_{p=0}^{n}\binom{n}{p} = 2^n$.
- O **Triângulo de Pascal** organiza os coeficientes binomiais, em que cada número é a soma dos dois que estão acima dele (Stifel), e a linha $n$ (começando em 0) contém $\binom{n}{0}, \dots, \binom{n}{n}$:
```
1
1 1
1 2 1
1 3 3 1
1 4 6 4 1
1 5 10 10 5 1
```
- Propriedades do triângulo: cada linha é **simétrica**, a soma da linha $n$ vale $2^n$, e vale o **Teorema das Colunas**: somando os elementos de uma coluna de cima para baixo, o resultado aparece na linha seguinte, deslocado uma coluna à direita:
$$\binom{p}{p} + \binom{p+1}{p} + \dots + \binom{n}{p} = \binom{n+1}{p+1}$$

## 5. Binômio de Newton

- O desenvolvimento de $(x + y)^n$ tem coeficientes dados pelos números binomiais:
$$(x+y)^n = \sum_{k=0}^{n} \binom{n}{k} \, x^{n-k} \, y^k$$
- O **termo geral**, que permite achar um termo específico sem desenvolver tudo, é o de posição $k+1$:
$$T_{k+1} = \binom{n}{k} \, x^{n-k} \, y^k$$
- A **soma dos coeficientes** de $(ax + by)^n$ obtém-se substituindo $x = y = 1$; no caso mais simples, $(x+y)^n$ tem soma $2^n$.
- Em $(x + y)^n$ há $n + 1$ termos, e os coeficientes equidistantes dos extremos são iguais (simetria da linha do Triângulo de Pascal).

## 6. Combinação com Repetição e Distribuições (Estrelas e Barras)

- A **combinação com repetição** conta as escolhas de $p$ itens entre $n$ tipos, sem ordem e com possibilidade de repetir tipos:
$$CR_{n,p} = \binom{n + p - 1}{p}$$
 Exemplo: escolher 4 bolas de sorvete entre 3 sabores, podendo repetir, dá $\binom{6}{4} = 15$ formas.
- A técnica das **estrelas e barras** dá o número de soluções inteiras **não negativas** da equação $x_1 + x_2 + \dots + x_k = n$ (distribuir $n$ objetos idênticos em $k$ caixas):
$$\binom{n + k - 1}{n}$$
 Exemplo: $x + y + z = 10$ tem $\binom{12}{2} = 66$ soluções não negativas.
- Para soluções **positivas** (cada variável pelo menos 1), distribui-se antes uma unidade a cada variável e resolve-se o problema restante: $x + y + z = 10$ com $x, y, z \geq 1$ tem $\binom{9}{2} = 36$ soluções.
- **Divisão em grupos:** ao repartir pessoas em grupos, se os grupos são **distintos** (têm nomes ou funções diferentes), escolhe-se grupo a grupo; se são **indistintos** e de mesmo tamanho, divide-se o resultado pelo fatorial do número de grupos iguais, para não contar a mesma divisão em ordens diferentes. Exemplo: 6 pessoas em 3 duplas **indistintas** dão $\dfrac{\binom{6}{2}\binom{4}{2}\binom{2}{2}}{3!} = 15$ divisões (e 90 se as duplas forem nomeadas).

## 7. Roteiro de Resolução e Aplicações Clássicas

- **Passos para decidir a ferramenta:**
 - **Passo 1:** a ordem importa? Teste: trocar a ordem dos elementos escolhidos gera um resultado **diferente**? Se sim, arranjo ou permutação; se não, combinação;
 - **Passo 2:** há repetição permitida ou elementos idênticos?
 - **Passo 3:** há restrições? Comece sempre pela posição ou etapa **mais restrita**;
 - **Passo 4:** se o enunciado diz "pelo menos" ou "não", considere a contagem pelo complementar.
- **Técnica do bloco:** quando elementos devem ficar **juntos**, trate-os como um único elemento e permute também dentro do bloco. Exemplo: os anagramas de "BRASIL" com A e S juntos são $2 \cdot 5! = 240$.
- **Técnica da separação:** quando elementos **não podem** ficar juntos, calcule o total e subtraia os casos em que ficam juntos. Exemplo: 5 pessoas em fila, com duas específicas **não vizinhas**: $5! - 2 \cdot 4! = 72$.
- **Aplicações geométricas frequentes:**
 - **Diagonais de um polígono de $n$ lados:** $\binom{n}{2} - n = \dfrac{n(n-3)}{2}$;
 - **Triângulos** com vértices em $n$ pontos, dos quais $k$ são colineares: $\binom{n}{3} - \binom{k}{3}$;
 - **Caminhos em grade** de $m$ passos para a direita e $n$ para cima: $\binom{m+n}{m}$.

## 8. Probabilidade: Fundamentos

- **Espaço amostral ($\Omega$):** conjunto de todos os resultados possíveis de um experimento aleatório; **evento** é qualquer subconjunto de $\Omega$.
- **Definição clássica**, válida para resultados **equiprováveis**:
$$P(A) = \frac{n(A)}{n(\Omega)} = \frac{\text{casos favoráveis}}{\text{casos possíveis}}$$
 Exemplo: a probabilidade de a soma de dois dados ser 7 é $6/36 = 1/6$.
- **Propriedades básicas:**
 - $0 \leq P(A) \leq 1$, com $P(\Omega) = 1$ e $P(\varnothing) = 0$;
 - **Evento complementar:** $P(\overline{A}) = 1 - P(A)$;
 - **Regra da união:** $P(A \cup B) = P(A) + P(B) - P(A \cap B)$, que se reduz à soma simples se os eventos forem **mutuamente exclusivos** ($A \cap B = \varnothing$).
- **Evento "pelo menos um":** costuma ser resolvido pelo complementar, $P(\text{pelo menos um}) = 1 - P(\text{nenhum})$.
- **Lei dos Grandes Números:** com muitas repetições de um experimento, a **frequência relativa** de um evento tende à sua probabilidade teórica.

## 9. Probabilidade Condicional, Independência e Bayes

- A **probabilidade condicional** de $A$ dado que $B$ ocorreu reduz o espaço amostral a $B$:
$$P(A \mid B) = \frac{P(A \cap B)}{P(B)}$$
- Rearranjando, obtém-se a **regra do produto**:
$$P(A \cap B) = P(B) \cdot P(A \mid B)$$
 Exemplo: em uma urna com 5 bolas vermelhas e 3 azuis, a probabilidade de retirar 2 vermelhas **sem reposição** é $\dfrac{5}{8} \cdot \dfrac{4}{7} = \dfrac{5}{14}$.
- Dois eventos são **independentes** quando a ocorrência de um não altera a probabilidade do outro:
$$P(A \cap B) = P(A) \cdot P(B) \qquad \Longleftrightarrow \qquad P(A \mid B) = P(A)$$
- O **diagrama de árvore** organiza situações sequenciais: multiplica-se ao longo de cada caminho e soma-se entre os caminhos que levam ao evento desejado.
- A **Lei da Probabilidade Total** calcula a probabilidade de um evento $A$ a partir de uma partição $B_1, \dots, B_n$ do espaço amostral:
$$P(A) = \sum_{i=1}^{n} P(B_i) \cdot P(A \mid B_i)$$
- O **Teorema de Bayes** inverte a condicionalidade, calculando a probabilidade de uma "causa" a partir de um efeito observado:
$$P(B_j \mid A) = \frac{P(B_j) \cdot P(A \mid B_j)}{\sum_{i} P(B_i) \cdot P(A \mid B_i)}$$
 Exemplo: se uma doença atinge 1% da população e um teste detecta 90% dos doentes, mas dá falso positivo em 5% dos saudáveis, a probabilidade de uma pessoa com teste positivo estar realmente doente é $\dfrac{0{,}9 \cdot 0{,}01}{0{,}9 \cdot 0{,}01 + 0{,}05 \cdot 0{,}99} \approx 15{,}4\%$.

## 10. Distribuições, Probabilidade Geométrica e Esperança

- **Distribuição binomial:** em $n$ tentativas **independentes** de um experimento com apenas dois resultados (sucesso, com probabilidade $p$, ou fracasso, com $1-p$), a probabilidade de exatamente $k$ sucessos é:
$$P(X = k) = \binom{n}{k} \, p^k \, (1-p)^{n-k}$$
 Exemplo: a probabilidade de obter exatamente 2 caras em 5 lançamentos de uma moeda justa é $\dbinom{5}{2} \left(\dfrac{1}{2}\right)^5 = \dfrac{5}{16}$.
- Na binomial, a média e a variância são:
$$E(X) = n \cdot p \qquad \text{e} \qquad \text{Var}(X) = n \cdot p \cdot (1-p)$$
- **Distribuição hipergeométrica** (amostragem **sem reposição**): em uma população de $N$ elementos com $K$ "sucessos", a probabilidade de, em uma amostra de $n$, obter exatamente $k$ sucessos é:
$$P(X = k) = \frac{\binom{K}{k}\binom{N-K}{n-k}}{\binom{N}{n}}$$
- **Probabilidade geométrica:** quando o espaço amostral é uma região contínua, a probabilidade é a razão entre as **medidas** (comprimento, área ou volume) da região favorável e da total. Exemplo: a chance de um dardo lançado ao acaso acertar uma região circular dentro de um alvo é a razão entre as áreas.
- **Esperança matemática (valor esperado):** média ponderada dos valores possíveis de uma variável pelas suas probabilidades:
$$E(X) = \sum_{i} x_i \cdot P(x_i)$$
 Exemplo: um jogo em que se ganham R$ 10 com probabilidade 1/6 e se perdem R$ 2 com probabilidade 5/6 tem $E = \dfrac{10}{6} - \dfrac{10}{6} = 0$, ou seja, é um jogo **justo**.

## 11. Matrizes Comparativas

### 11.1 Tipos de Agrupamento

| Tipo | Ordem importa? | Repetição? | Fórmula | Exemplo |
|---|---|---|---|---|
| **Arranjo simples** | Sim | Não | $\dfrac{n!}{(n-p)!}$ | Pódio com 3 entre 10: 720 |
| **Arranjo com repetição** | Sim | Sim | $n^p$ | Senha de 4 dígitos: 10.000 |
| **Permutação simples** | Sim (todos os $n$) | Não | $n!$ | Anagramas de LIVRO: 120 |
| **Permutação com repetição** | Sim | Elementos iguais | $\dfrac{n!}{a!\,b!\cdots}$ | Anagramas de ARARA: 10 |
| **Permutação circular** | Sim (posição relativa) | Não | $(n-1)!$ | 5 pessoas na mesa redonda: 24 |
| **Combinação simples** | Não | Não | $\dbinom{n}{p}$ | Comissão de 3 entre 8: 56 |
| **Combinação com repetição** | Não | Sim | $\dbinom{n+p-1}{p}$ | 4 bolas entre 3 sabores: 15 |

### 11.2 Ferramentas de Probabilidade por Tipo de Situação

| Situação do enunciado | Ferramenta | Expressão |
|---|---|---|
| Resultados equiprováveis | Definição clássica | $n(A)/n(\Omega)$ |
| "Não ocorrer" ou "pelo menos um" | Complementar | $1 - P(A)$ |
| "A **ou** B" | Regra da união | $P(A) + P(B) - P(A \cap B)$ |
| "A **e** B", eventos independentes | Produto | $P(A) \cdot P(B)$ |
| "A e B", **sem reposição** | Produto condicional | $P(A) \cdot P(B \mid A)$ |
| Sabe-se que B ocorreu | Condicional | $P(A \cap B)/P(B)$ |
| Descobrir a causa a partir do efeito | Bayes | $\dfrac{P(B_j)P(A\mid B_j)}{P(A)}$ |
| $n$ tentativas idênticas e independentes | Binomial | $\binom{n}{k}p^k(1-p)^{n-k}$ |
| Amostra sem reposição de grupos | Hipergeométrica | $\binom{K}{k}\binom{N-K}{n-k}\big/\binom{N}{n}$ |
| Região contínua | Geométrica | Medida favorável / medida total |
| Ganho ou perda médios | Esperança | $\sum x_i \, P(x_i)$ |

> [!quote] Strategic Counterpoint
> * **Erros Clássicos:**
> - Usar **arranjo quando a ordem não importa** (ou combinação quando importa): o teste é perguntar se trocar a ordem dos escolhidos produz um resultado distinto. Um erro relacionado, em probabilidade, é contar o numerador **com ordem** e o denominador **sem ordem** (ou o inverso); ambos devem seguir o mesmo critério.
> - Aplicar a **regra do produto como se os eventos fossem independentes** em situações **sem reposição**: ao retirar uma bola e não devolvê-la, a probabilidade da segunda retirada muda, e é preciso usar $P(B \mid A)$.
> - Ignorar a **taxa-base** em problemas de Bayes: um teste com 90% de sensibilidade pode resultar em apenas cerca de 15% de chance de doença para um resultado positivo quando a doença é rara, o que contraria a intuição.
> - Cair na **falácia do apostador**: após cinco caras seguidas, a probabilidade de cara no próximo lançamento de uma moeda justa continua sendo 1/2, pois os lançamentos são independentes.
> - Esquecer **restrições** na contagem (por exemplo, número que "não começa por zero"): comece sempre pela posição mais restrita para não precisar corrigir depois.
>
> * **Distinção Crítica:**
> - **Eventos independentes** vs. **eventos mutuamente exclusivos:** independentes são aqueles em que a ocorrência de um **não altera** a probabilidade do outro ($P(A \cap B) = P(A)P(B)$); mutuamente exclusivos são os que **não podem ocorrer juntos** ($A \cap B = \varnothing$). Os conceitos são quase opostos: se dois eventos de probabilidade positiva são mutuamente exclusivos, saber que um ocorreu garante que o outro **não** ocorreu, logo eles são **dependentes**. Confundi-los leva a usar a soma onde se deveria multiplicar, e vice-versa.
>
> * **Aplicação Prática:**
> - Nas **loterias**, o cálculo $\binom{60}{6} = 50.063.860$ mostra que a chance de acertar a sena com um jogo simples é de cerca de 1 em 50 milhões; em **diagnóstico médico**, o Teorema de Bayes explica por que exames de triagem com resultado positivo exigem confirmação; e em **segurança digital**, o crescimento exponencial do arranjo com repetição ($62^8$, por exemplo) justifica a recomendação de senhas longas e variadas.

---

Tags: [[Matemática]] [[Análise Combinatória]] [[Probabilidade]]
