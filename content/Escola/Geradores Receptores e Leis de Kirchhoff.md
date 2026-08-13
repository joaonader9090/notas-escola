Tags: [[Física]] [[Eletrodinâmica]] [[Geradores, Receptores e Leis de Kirchhoff]]

> [!abstract]
> Em um circuito elétrico, **geradores** são os dispositivos que convertem outras formas de energia (mecânica, química, luminosa) em energia elétrica, fornecendo-a ao circuito, enquanto **receptores** fazem o caminho inverso de forma parcial: convertem energia elétrica em uma forma de energia útil que **não é exclusivamente térmica** — como energia mecânica em um motor ou energia química ao carregar uma bateria. Ambos são caracterizados por uma resistência interna, responsável por dissipação de energia por efeito Joule, e por uma grandeza característica (força eletromotriz no gerador, força contraeletromotriz no receptor) que define a conversão de energia não-térmica. Quando o circuito se torna complexo, com múltiplas malhas e nós, a análise direta por associação de resistores deixa de ser suficiente, exigindo as **Leis de Kirchhoff** — a **Lei dos Nós**, expressão da conservação da carga elétrica, e a **Lei das Malhas**, expressão da conservação de energia —, que juntas permitem montar um sistema de equações capaz de determinar todas as correntes de qualquer circuito, por mais ramificado que seja.

> [!info] Nota metodológica
> Esta nota foi elaborada sem apostila-fonte fornecida, a partir de conhecimento consolidado de Física (Eletrodinâmica). O componente de **rastreabilidade `(p. X)`** do método está, portanto, **inoperante** nesta nota — não há página de origem a citar. Caso deseje cruzar este conteúdo com uma apostila ou livro específico, envie o material e a nota pode ser reconstruída com citação de página ativa.

## 1. Geradores Elétricos

- **Gerador** é todo dispositivo que converte outra forma de energia em **energia elétrica**, fornecendo energia ao circuito — pilhas, baterias, dínamos e células fotovoltaicas são exemplos.
- **Equação do gerador**: **U = ε − r·i**, onde:
  - **ε (força eletromotriz — fem)**: energia elétrica fornecida por unidade de carga que atravessa o gerador (unidade: volt). Apesar do nome, **não é uma força**, é uma razão energia/carga.
  - **r**: resistência interna do gerador, responsável pela dissipação de parte da energia gerada.
  - **U**: tensão (ddp) nos terminais do gerador, disponível para o circuito externo.
- **Potências**:
  - Potência total gerada: **Pt = ε·i**
  - Potência dissipada internamente (efeito Joule): **Pd = r·i²**
  - Potência útil (entregue ao circuito externo): **Pu = U·i = Pt − Pd**
- **Rendimento do gerador**: **η = Pu/Pt = U/ε**
- **Curva característica** (gráfico U × i): reta decrescente.
  - Em **circuito aberto** (i = 0): U = ε (a tensão nos terminais iguala a fem).
  - Em **curto-circuito** (U = 0): **i_cc = ε/r** (corrente de curto-circuito, máxima possível para aquele gerador).

## 2. Receptores Elétricos

- **Receptor** é todo dispositivo que converte energia elétrica em outra forma de energia **que não seja exclusivamente térmica** — motores elétricos (energia mecânica) e baterias em processo de carga (energia química) são os exemplos clássicos.
- **Equação do receptor**: **U = ε' + r'·i**, onde:
  - **ε' (força contraeletromotriz — fcem)**: energia elétrica por unidade de carga que o receptor converte em energia útil não-térmica.
  - **r'**: resistência interna do receptor.
  - **U**: tensão (ddp) aplicada sobre o receptor.
- **Potências**:
  - Potência total recebida: **Pt = U·i**
  - Potência útil (convertida em energia não-térmica): **Pu = ε'·i**
  - Potência dissipada internamente (efeito Joule): **Pd = r'·i²**
- **Rendimento do receptor**: **η = Pu/Pt = ε'/U**
- Um **resistor puro** não é um receptor: toda a energia elétrica que recebe é convertida em calor, sem fcem (ε' = 0), logo U = r·i simplesmente.

## 3. Associação de Geradores e Receptores em um Circuito

- Em um circuito simples com um gerador e um receptor em série (mais resistência externa R): **i = (ε − ε') / (r + r' + R)**.
- **Condição de funcionamento**: é necessário que **ε > ε'**, ou seja, a fem do gerador deve superar a fcem do receptor para que a corrente circule no sentido esperado.
- **Geradores em série**: as fems se somam (ε_eq = ε₁ + ε₂ + ...) e as resistências internas se somam (r_eq = r₁ + r₂ + ...).
- **Geradores idênticos em paralelo**: a fem equivalente permanece igual à de um gerador (ε_eq = ε), mas a resistência interna equivalente diminui (r_eq = r/n, para n geradores) — configuração usada para fornecer correntes maiores sem elevar a tensão.

## 4. Primeira Lei de Kirchhoff (Lei dos Nós)

- **Enunciado**: em qualquer **nó** de um circuito (ponto de encontro de três ou mais condutores), a **soma das correntes que entram** é igual à **soma das correntes que saem**.
  - **ΣI(entram) = ΣI(saem)**
- **Fundamento físico**: é uma expressão direta da **conservação da carga elétrica** — em regime estacionário, a carga não pode se acumular nem ser criada num nó.
- É a lei que permite tratar a **divisão e a reunião de correntes** em circuitos com múltiplos ramos e malhas, situação em que a simples associação série/paralelo de resistores não é mais suficiente.

## 5. Segunda Lei de Kirchhoff (Lei das Malhas)

- **Enunciado**: percorrendo qualquer **malha fechada** de um circuito num sentido arbitrário, a **soma algébrica das variações de potencial (ddp)** encontradas ao longo do percurso é igual a **zero**.
  - **ΣU = 0** (ao longo de uma malha fechada)
- **Fundamento físico**: é uma expressão da **conservação de energia** — toda a energia fornecida pelos geradores de uma malha fechada é integralmente consumida por resistores e receptores presentes nela.
- **Convenção de sinais** ao percorrer a malha no sentido escolhido:
  - Atravessar um **resistor a favor** do sentido da corrente: queda de potencial, **−R·i**.
  - Atravessar um **resistor contra** o sentido da corrente: ganho de potencial, **+R·i**.
  - Atravessar um **gerador do polo − para o polo +** (a favor da fem): **+ε**.
  - Atravessar um **gerador do polo + para o polo −** (contra a fem): **−ε**.
  - Para **receptores**, a convenção de sinal da fcem é invertida em relação ao gerador (o receptor "consome" energia no sentido da corrente).

## 6. Método de Resolução de Circuitos com as Leis de Kirchhoff

- **Passo 1**: identificar todos os **nós** do circuito e atribuir, arbitrariamente, um sentido para a corrente em cada ramo.
- **Passo 2**: aplicar a **1ª Lei de Kirchhoff** em (n − 1) nós independentes, sendo n o número total de nós (o último nó é sempre uma combinação linear dos anteriores, não fornecendo informação nova).
- **Passo 3**: identificar as **malhas independentes** do circuito e aplicar a **2ª Lei de Kirchhoff** em cada uma delas, respeitando a convenção de sinais.
- **Passo 4**: resolver o **sistema de equações lineares** resultante para encontrar as correntes de cada ramo.
- Se alguma corrente resultar em valor **negativo**, isso não é um erro de cálculo: significa apenas que o **sentido real da corrente é oposto** ao sentido arbitrado no Passo 1.

## 7. Matriz Comparativa

**Gerador × Receptor**

| Característica | Gerador | Receptor |
|---|---|---|
| **Conversão de energia** | Outra forma → energia elétrica | Energia elétrica → outra forma (não exclusivamente térmica) |
| **Equação** | U = ε − r·i | U = ε' + r'·i |
| **Grandeza característica** | Força eletromotriz (fem, ε) | Força contraeletromotriz (fcem, ε') |
| **Potência útil** | Pu = U·i | Pu = ε'·i |
| **Rendimento** | η = U/ε | η = ε'/U |
| **Exemplo** | Pilha, dínamo, célula fotovoltaica | Motor elétrico, bateria em carga |

**1ª Lei de Kirchhoff × 2ª Lei de Kirchhoff**

| Característica | Lei dos Nós (1ª) | Lei das Malhas (2ª) |
|---|---|---|
| **Grandeza conservada** | Carga elétrica | Energia |
| **Onde se aplica** | Nós (encontro de 3+ condutores) | Malhas fechadas |
| **Enunciado resumido** | ΣI(entram) = ΣI(saem) | ΣU = 0 no percurso fechado |
| **Quando é indispensável** | Circuitos com divisão/reunião de correntes | Circuitos com mais de um gerador ou malhas não redutíveis a série/paralelo |

> [!quote] Strategic Counterpoint
> * **Erros Clássicos:** confundir a **fem (ε)** com a **tensão nos terminais (U)** do gerador é o erro mais recorrente — elas só coincidem no caso particular de **circuito aberto** (i = 0); outro deslize é achar que qualquer dispositivo com resistência é um "receptor" — um resistor puro converte 100% da energia elétrica em calor (fcem = 0) e **não é** um receptor no sentido técnico; erros de **sinal** na aplicação da 2ª Lei de Kirchhoff (inverter a convenção ao atravessar um gerador ou resistor) são a fonte mais comum de erro em exercícios de circuitos com múltiplas malhas.
> * **Distinção Crítica:** a diferença formal entre **resistor puro** e **receptor** não é a complexidade do dispositivo, mas a presença de uma **força contraeletromotriz**: o resistor obedece a U = R·i (sem termo de conversão útil), enquanto o receptor obedece a U = ε' + r'·i, dissipando **apenas uma fração** da energia recebida como calor e convertendo o restante em energia mecânica, química etc. Da mesma forma, a **Lei dos Nós** (conservação de carga, aplicada pontualmente) não deve ser confundida com a **Lei das Malhas** (conservação de energia, aplicada ao longo de um percurso fechado) — são leis de naturezas físicas distintas que se complementam, não são intercambiáveis.
> * **Aplicação Prática:** o cálculo do **rendimento de um motor elétrico real** (η = ε'/U) é a base para comparar eficiência energética de eletrodomésticos e motores industriais; no sistema elétrico automotivo, o **alternador atua como gerador** carregando a **bateria como receptor** — um exemplo direto de como os dois conceitos coexistem no mesmo circuito físico em situações do cotidiano.

Tags: [[Física]] [[Eletrodinâmica]] [[Geradores, Receptores e Leis de Kirchhoff]]
