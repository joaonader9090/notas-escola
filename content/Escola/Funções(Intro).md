Tags: [[matemática]] [[funções]] [[álgebra]]

> [!abstract] Uma função é uma regra matemática que estabelece uma relação de dependência entre dois conjuntos, onde cada elemento de um conjunto de partida corresponde a um único elemento em um conjunto de chegada. Este conceito é fundamental para modelar fenômenos onde uma variável depende diretamente de outra.

## 1. Definição e Elementos Fundamentais

Para que uma relação seja considerada uma função ($f: A \rightarrow B$), duas condições devem ser estritamente seguidas:

- **Totalidade do Domínio:** Jamais podem sobrar elementos no conjunto de partida ($A$).
    
- **Unicidade da Imagem:** Cada elemento do conjunto de partida possui um **único** correspondente no conjunto de chegada ($B$).
    

### Componentes da Função

- **Domínio ($D$):** É o conjunto de partida ($A$).
    
- **Contradomínio ($CD$):** É o conjunto de chegada ($B$).
    
- **Imagem ($Im$):** Conjunto formado apenas pelos elementos do contradomínio que possuem um correspondente no domínio.
    

---

## 2. Restrições de Domínio (Casos Peculiares)

Na análise de funções reais, certas operações impõem restrições ao domínio para garantir a existência do valor da função:

- **Denominadores:** O denominador de uma fração jamais pode ser igual a zero. Exemplo: Em $f(x) = \frac{2x+3}{x-2}$, temos $x-2 \neq 0$, logo $D(f) = \mathbb{R} - \{2\}$.
    
- **Radicais de índice par:** O radicando não pode ser negativo. Exemplo: Em $g(x) = \sqrt{x-5}$, temos $x-5 \geq 0$, logo $x \geq 5$.
    
- **Radical par no denominador:** O radicando deve ser estritamente positivo. Exemplo: Em $h(x) = \frac{2x}{\sqrt{x-3}}$, temos $x-3 > 0$, logo $x > 3$.
    

---

## 3. Classificação quanto à Simetria e Correspondência

### Simetria

- **Função Par:** Quando $f(x) = f(-x)$. O gráfico é simétrico em relação ao eixo das ordenadas (eixo $y$). Exemplo: $f(x) = x^2$.
    
- **Função Ímpar:** Quando $f(x) = -f(-x)$. O gráfico é simétrico em relação à origem do plano cartesiano. Exemplo: $f(x) = x^3$.
    

### Correspondência (Injetora, Sobrejetora e Bijetora)

- **Função Injetora:** Elementos diferentes do domínio possuem imagens diferentes ($x_1 \neq x_2 \rightarrow f(x_1) \neq f(x_2)$).
    
- **Função Sobrejetora:** Quando o conjunto Imagem é igual ao Contradomínio ($Im(f) = B$).
    
- **Função Bijetora:** É a função que é simultaneamente injetora e sobrejetora.
    

---

## 4. Funções Compostas e Inversas

- **Função Composta:** Representada por $(g \circ f)(x) = g(f(x))$, ocorre quando aplicamos uma função sobre o resultado de outra.
    
- **Função Inversa ($f^{-1}$):** Somente funções **bijetoras** admitem inversa.
    
    - **Regra Prática:** Troque $x$ por $y$, depois isole o novo $y$.
        
    - **Gráfico:** Os gráficos de $f$ e $f^{-1}$ são simétricos em relação à bissetriz dos quadrantes ímpares ($y=x$).
        

---

## 5. Análise Gráfica

- **Teste da Linha Vertical:** Nem toda linha contínua é função. Se uma linha vertical tocar o gráfico mais de uma vez, não é função.
    
- **Teste da Injetividade:** Trace linhas horizontais; se tocarem o gráfico mais de uma vez, a função **não** é injetora.
    
- **Crescimento:** Uma função é crescente se, ao aumentar $x$, o valor de $y$ também aumenta. É decrescente se $y$ diminui conforme $x$ aumenta.
    

> [!quote] Strategic Counterpoint Um erro crítico no estudo de funções é focar apenas na álgebra e ignorar a análise visual. No **[[ENEM]]**, muitas questões exigem apenas a interpretação do domínio e imagem através de gráficos reais. Lembre-se que as **raízes da função** são os valores de $x$ onde o gráfico toca o eixo horizontal (onde $f(x)=0$). Outro ponto de atenção é a **Função Composta**: a ordem importa; geralmente $f(g(x)) \neq g(f(x))$. O domínio da composta deve respeitar as restrições tanto da função interna quanto da externa.

---
