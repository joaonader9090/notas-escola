# Física Eletrostática: Guia de Estudo Técnico

[!ABSTRACT] **Analisar** a eletrostática exige a compreensão das cargas em repouso como fontes de perturbação no espaço-tempo (campos). É imperativo **sintetizar** a Lei de Conservação de Cargas: em sistemas eletricamente isolados, o somatório algébrico das cargas (\sum Q) permanece invariante, fundamentando toda a análise de transferência e equilíbrio.

## 1. Fundamentos e Eletrização de Corpos

### Natureza e Quantização da Carga

A carga elétrica é uma propriedade quantizada, existindo apenas como múltiplos inteiros da carga elementar (e).

- **Carga Elementar (****e****):** 1,6 \cdot 10^{-19} \text{ } [C]
- **Equação de Quantização:** Q = n \cdot e (onde n \in \mathbb{Z})
- **Estado Elétrico do Sistema:**
    - N_p = N_e \Rightarrow **Neutro**
    - N_p > N_e \Rightarrow **Positivo** (Perda de e^-)
    - N_p < N_e \Rightarrow **Negativo** (Ganho de e^-)

### Mecanismos de Transferência (Eletrização)

[!FORMULA] **Processos Técnicos**

1. **Atrito:** Fricção entre materiais distintos \Rightarrow Transferência de e^- conforme a **Série Triboelétrica** \Rightarrow Cargas finais de sinais opostos (Q_A = -Q_B).
2. **Contato:** Fluxo de e^- entre condutores até o equilíbrio de potencial.
    - _Condutores Idênticos:_ Q_{final} = \frac{\sum Q}{n}
    - _Sinal:_ Cargas finais sempre possuem o mesmo sinal.
3. **Indução:** Redistribuição de cargas via proximidade (Indutor e Induzido).
    - _Aterramento:_ Permite a neutralização ou carga permanente do induzido com sinal oposto ao do indutor.

[!IMPORTANT] **Conexão Crítica: Atração vs. Repulsão**

- **Atração:** Ocorre entre cargas de sinais opostos **ou** entre um corpo eletrizado e um corpo neutro (via indução local).
- **Repulsão:** Ocorre **estritamente** entre corpos de mesmo sinal.

--------------------------------------------------------------------------------

## 2. Interações: Força e Campo Elétrico

O campo elétrico (E) elimina a necessidade de "ação à distância", definindo a força (F) como uma resposta local da carga à modificação do espaço.

### Lei de Coulomb e Vetor Campo

- **Magnitude da Força (****F****):** F = k \cdot \frac{|Q_1 \cdot Q_2|}{d^2} \text{ } [N]
    - _Constante (__k__):_ 9 \cdot 10^9 \text{ } [N \cdot m^2/C^2]
    - _Lógica de Proporcionalidade:_ \uparrow 2 \cdot d \Rightarrow \downarrow \frac{1}{4} \cdot F (Lei do Inverso do Quadrado).
- **Intensidade do Campo (****E****):** E = \frac{F}{|q|} ou E = k \cdot \frac{|Q|}{d^2} \text{ } [N/C] \text{ ou } [V/m]

[!FORMULA] **Dinâmica Vetorial**

- **Carga Fonte (****Q > 0****):** Vetor campo divergente (linhas saem).
- **Carga Fonte (****Q < 0****):** Vetor campo convergente (linhas entram).
- **Interação (****q****):**
    - q > 0 \Rightarrow \vec{F} e \vec{E} têm o mesmo sentido.
    - q < 0 \Rightarrow \vec{F} e \vec{E} têm sentidos opostos.

[!IMPORTANT] **Síntese de Resolução: Equilíbrio de Carga** O campo resultante (E_R) em qualquer ponto P é a **soma vetorial** de todos os campos individuais: \vec{E}_R = \sum \vec{E}_n. O equilíbrio ocorre quando \sum \vec{F} = 0.

--------------------------------------------------------------------------------

## 3. Potencial, Trabalho e Energia

Diferente do campo (vetorial), o potencial (V) é uma grandeza escalar, facilitando o cálculo de energia em sistemas complexos.

### Potencial Elétrico (V) e DDP (U)

- **Potencial de Carga Puntiforme:** V = k \cdot \frac{Q}{d} \text{ } [V] (O sinal da carga Q altera o valor de V).
- **Superfícies Equipotenciais:** Regiões onde V é constante \Rightarrow W = 0 para deslocamento sobre a superfície.
- **Movimento Espontâneo:**
    - Cargas Q > 0 \Rightarrow Buscam menor potencial (\downarrow V).
    - Cargas Q < 0 \Rightarrow Buscam maior potencial (\uparrow V).

### Trabalho (W) e Energia Potencial (E_p)

[!FORMULA] **Relações Energéticas**

- **Energia Potencial:** E_p = k \cdot \frac{Q \cdot q}{d} = q \cdot V \text{ } [J]
- **Trabalho da Força Elétrica:** W_{A \to B} = q \cdot (V_A - V_B)
- **Conservação:** W = -\Delta E_p (Trabalho é o negativo da variação de energia potencial).
- **Teorema Trabalho-Energia:** W = \Delta E_c (O trabalho resulta em variação de energia cinética).
- **Campo Uniforme (CEU):** E \cdot d = V

--------------------------------------------------------------------------------

## 4. Condutores em Equilíbrio e Capacitância

### Equilíbrio Eletrostático

Em um condutor em equilíbrio, as cargas residem na superfície externa para minimizar a repulsão.

- **Campo Interno (****E_{int}****):** 0 \text{ } [N/C].
- **Potencial (****V****):** Constante em todo o condutor (interno e superfície).
- **Equilíbrio entre Esferas:** Ao conectar duas esferas de raios R_A e R_B, o equilíbrio exige V_A = V_B, resultando na relação: \frac{Q_A}{R_A} = \frac{Q_B}{R_B}.
    - _Insight:_ Maior raio \Rightarrow maior capacidade de carga.
- **Gaiola de Faraday:** Blindagem eletrostática resultante de E_{int} = 0. No contato interno, toda a carga é transferida para a face externa do receptor.

### Capacitores (Armazenamento de Energia)

Dispositivos que armazenam carga (Q) sob uma DDP (V).

[!FORMULA] **Parâmetros Técnicos**

- **Capacitância Geral:** C = \frac{Q}{V} \text{ } [F] (Farad).
- **Capacitor de Placas Paralelas:** C = \frac{\kappa \cdot \epsilon_0 \cdot A}{d}
    - \kappa: Constante dielétrica; A: Área das placas; d: Distância.
- **Energia Armazenada:** E_p = \frac{1}{2} \cdot Q \cdot V = \frac{1}{2} \cdot C \cdot V^2 \text{ } [J].

### Associações de Capacitores

1. **Série:** Carga Q é constante em todos.
    - \frac{1}{C_{eq}} = \sum \frac{1}{C_n}
    - V_{total} = \sum V_n
2. **Paralelo:** DDP V é constante em todos.
    - C_{eq} = \sum C_n
    - Q_{total} = \sum Q_n

[!IMPORTANT] **Dielétricos e Rigidez** A inserção de dielétricos aumenta a capacitância (\uparrow C) ao reduzir o campo interno para uma mesma carga. O limite de operação é a **Rigidez Dielétrica**, campo máximo que o isolante suporta antes de se tornar condutor.# Física Eletrostática: Guia de Estudo Técnico

[!ABSTRACT] **Analisar** a eletrostática exige a compreensão das cargas em repouso como fontes de perturbação no espaço-tempo (campos). É imperativo **sintetizar** a Lei de Conservação de Cargas: em sistemas eletricamente isolados, o somatório algébrico das cargas (\sum Q) permanece invariante, fundamentando toda a análise de transferência e equilíbrio.

## 1. Fundamentos e Eletrização de Corpos

### Natureza e Quantização da Carga

A carga elétrica é uma propriedade quantizada, existindo apenas como múltiplos inteiros da carga elementar (e).

- **Carga Elementar (****e****):** 1,6 \cdot 10^{-19} \text{ } [C]
- **Equação de Quantização:** Q = n \cdot e (onde n \in \mathbb{Z})
- **Estado Elétrico do Sistema:**
    - N_p = N_e \Rightarrow **Neutro**
    - N_p > N_e \Rightarrow **Positivo** (Perda de e^-)
    - N_p < N_e \Rightarrow **Negativo** (Ganho de e^-)

### Mecanismos de Transferência (Eletrização)

[!FORMULA] **Processos Técnicos**

1. **Atrito:** Fricção entre materiais distintos \Rightarrow Transferência de e^- conforme a **Série Triboelétrica** \Rightarrow Cargas finais de sinais opostos (Q_A = -Q_B).
2. **Contato:** Fluxo de e^- entre condutores até o equilíbrio de potencial.
    - _Condutores Idênticos:_ Q_{final} = \frac{\sum Q}{n}
    - _Sinal:_ Cargas finais sempre possuem o mesmo sinal.
3. **Indução:** Redistribuição de cargas via proximidade (Indutor e Induzido).
    - _Aterramento:_ Permite a neutralização ou carga permanente do induzido com sinal oposto ao do indutor.

[!IMPORTANT] **Conexão Crítica: Atração vs. Repulsão**

- **Atração:** Ocorre entre cargas de sinais opostos **ou** entre um corpo eletrizado e um corpo neutro (via indução local).
- **Repulsão:** Ocorre **estritamente** entre corpos de mesmo sinal.

--------------------------------------------------------------------------------

## 2. Interações: Força e Campo Elétrico

O campo elétrico (E) elimina a necessidade de "ação à distância", definindo a força (F) como uma resposta local da carga à modificação do espaço.

### Lei de Coulomb e Vetor Campo

- **Magnitude da Força (****F****):** F = k \cdot \frac{|Q_1 \cdot Q_2|}{d^2} \text{ } [N]
    - _Constante (__k__):_ 9 \cdot 10^9 \text{ } [N \cdot m^2/C^2]
    - _Lógica de Proporcionalidade:_ \uparrow 2 \cdot d \Rightarrow \downarrow \frac{1}{4} \cdot F (Lei do Inverso do Quadrado).
- **Intensidade do Campo (****E****):** E = \frac{F}{|q|} ou E = k \cdot \frac{|Q|}{d^2} \text{ } [N/C] \text{ ou } [V/m]

[!FORMULA] **Dinâmica Vetorial**

- **Carga Fonte (****Q > 0****):** Vetor campo divergente (linhas saem).
- **Carga Fonte (****Q < 0****):** Vetor campo convergente (linhas entram).
- **Interação (****q****):**
    - q > 0 \Rightarrow \vec{F} e \vec{E} têm o mesmo sentido.
    - q < 0 \Rightarrow \vec{F} e \vec{E} têm sentidos opostos.

[!IMPORTANT] **Síntese de Resolução: Equilíbrio de Carga** O campo resultante (E_R) em qualquer ponto P é a **soma vetorial** de todos os campos individuais: \vec{E}_R = \sum \vec{E}_n. O equilíbrio ocorre quando \sum \vec{F} = 0.

--------------------------------------------------------------------------------

## 3. Potencial, Trabalho e Energia

Diferente do campo (vetorial), o potencial (V) é uma grandeza escalar, facilitando o cálculo de energia em sistemas complexos.

### Potencial Elétrico (V) e DDP (U)

- **Potencial de Carga Puntiforme:** V = k \cdot \frac{Q}{d} \text{ } [V] (O sinal da carga Q altera o valor de V).
- **Superfícies Equipotenciais:** Regiões onde V é constante \Rightarrow W = 0 para deslocamento sobre a superfície.
- **Movimento Espontâneo:**
    - Cargas Q > 0 \Rightarrow Buscam menor potencial (\downarrow V).
    - Cargas Q < 0 \Rightarrow Buscam maior potencial (\uparrow V).

### Trabalho (W) e Energia Potencial (E_p)

[!FORMULA] **Relações Energéticas**

- **Energia Potencial:** E_p = k \cdot \frac{Q \cdot q}{d} = q \cdot V \text{ } [J]
- **Trabalho da Força Elétrica:** W_{A \to B} = q \cdot (V_A - V_B)
- **Conservação:** W = -\Delta E_p (Trabalho é o negativo da variação de energia potencial).
- **Teorema Trabalho-Energia:** W = \Delta E_c (O trabalho resulta em variação de energia cinética).
- **Campo Uniforme (CEU):** E \cdot d = V

--------------------------------------------------------------------------------

## 4. Condutores em Equilíbrio e Capacitância

### Equilíbrio Eletrostático

Em um condutor em equilíbrio, as cargas residem na superfície externa para minimizar a repulsão.

- **Campo Interno (****E_{int}****):** 0 \text{ } [N/C].
- **Potencial (****V****):** Constante em todo o condutor (interno e superfície).
- **Equilíbrio entre Esferas:** Ao conectar duas esferas de raios R_A e R_B, o equilíbrio exige V_A = V_B, resultando na relação: \frac{Q_A}{R_A} = \frac{Q_B}{R_B}.
    - _Insight:_ Maior raio \Rightarrow maior capacidade de carga.
- **Gaiola de Faraday:** Blindagem eletrostática resultante de E_{int} = 0. No contato interno, toda a carga é transferida para a face externa do receptor.

### Capacitores (Armazenamento de Energia)

Dispositivos que armazenam carga (Q) sob uma DDP (V).

[!FORMULA] **Parâmetros Técnicos**

- **Capacitância Geral:** C = \frac{Q}{V} \text{ } [F] (Farad).
- **Capacitor de Placas Paralelas:** C = \frac{\kappa \cdot \epsilon_0 \cdot A}{d}
    - \kappa: Constante dielétrica; A: Área das placas; d: Distância.
- **Energia Armazenada:** E_p = \frac{1}{2} \cdot Q \cdot V = \frac{1}{2} \cdot C \cdot V^2 \text{ } [J].

### Associações de Capacitores

1. **Série:** Carga Q é constante em todos.
    - \frac{1}{C_{eq}} = \sum \frac{1}{C_n}
    - V_{total} = \sum V_n
2. **Paralelo:** DDP V é constante em todos.
    - C_{eq} = \sum C_n
    - Q_{total} = \sum Q_n

[!IMPORTANT] **Dielétricos e Rigidez** A inserção de dielétricos aumenta a capacitância (\uparrow C) ao reduzir o campo interno para uma mesma carga. O limite de operação é a **Rigidez Dielétrica**, campo máximo que o isolante suporta antes de se tornar condutor.