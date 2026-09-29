Tags: [[Física]] [[Eletromagnetismo]] [[Magnetismo]]

> [!abstract]
> A porção magnética do Eletromagnetismo estuda os fenômenos associados ao **campo magnético**, desde o magnetismo natural de ímãs até sua relação profunda com **cargas elétricas em movimento** — relação que unifica, na Física, os fenômenos elétricos e magnéticos em um único campo teórico. Uma carga elétrica em movimento dentro de um campo magnético sofre a ação da **Força de Lorentz**, responsável por trajetórias curvas e circulares; um fio percorrido por corrente elétrica, por sua vez, sofre a **Força de Ampère** quando imerso em um campo magnético externo. De forma complementar, toda corrente elétrica também **cria** um campo magnético ao seu redor, descrito por fórmulas específicas para fios retilíneos, espiras circulares e solenoides. O elo final entre eletricidade e magnetismo é dado pela **Indução Eletromagnética**, fenômeno em que a variação de um campo magnético através de um circuito gera uma corrente elétrica induzida — descrito quantitativamente pela **Lei de Faraday** e, quanto ao sentido dessa corrente, pela **Lei de Lenz**. Esse conjunto de leis fundamenta o funcionamento de motores elétricos, geradores e transformadores, pilares da geração e do uso de energia elétrica em larga escala.

## 1. Ímãs e Campo Magnético

- Todo ímã possui dois **polos magnéticos**, denominados **polo norte** e **polo sul**, que não podem ser isolados — ao dividir um ímã ao meio, obtêm-se dois novos ímãs, cada um novamente com dois polos (não existem monopolos magnéticos isolados na natureza clássica).
- Polos de mesmo nome se **repelem**; polos de nomes diferentes se **atraem**.
- O **campo magnético** ($\vec{B}$) é representado por **linhas de campo** que saem do polo norte e entram no polo sul, pela **convenção externa** ao ímã, formando sempre **curvas fechadas** (ao contrário das linhas de campo elétrico, que se originam e terminam em cargas).
- A própria Terra se comporta como um grande ímã, com seu **campo magnético terrestre** sendo responsável pela orientação das bússolas — o polo norte magnético terrestre fica próximo ao polo sul geográfico, e vice-versa.

## 2. Força Magnética sobre uma Carga Elétrica (Força de Lorentz)

- Uma carga elétrica $q$, movendo-se com velocidade $\vec{v}$ dentro de um campo magnético $\vec{B}$, sofre a ação de uma força magnética cuja intensidade é dada por:
$$F = |q| \cdot v \cdot B \cdot \text{sen}(\theta)$$
 onde $\theta$ é o ângulo formado entre os vetores velocidade e campo magnético.
- Consequências importantes dessa fórmula:
 - Se a carga estiver **parada** ($v = 0$) ou se mover **paralelamente** ao campo ($\theta = 0°$ ou $180°$), a força magnética é **nula**;
 - A força magnética é **máxima** quando a velocidade é **perpendicular** ao campo magnético ($\theta = 90°$).
- A **direção e o sentido** da força são determinados pela **regra da mão direita** (para cargas positivas) ou pela regra da mão esquerda / inversão do sentido (para cargas negativas): a força resultante é sempre **perpendicular** tanto à velocidade quanto ao campo magnético.
- Como a força magnética é sempre perpendicular à velocidade da carga, ela **nunca realiza trabalho** sobre a partícula — apenas altera a direção do movimento, nunca o módulo da velocidade.

## 3. Movimento de Cargas em Campos Magnéticos Uniformes

- Quando uma carga entra em um campo magnético uniforme com velocidade **perpendicular** ao campo, a força magnética atua como **força centrípeta**, fazendo a carga descrever uma **trajetória circular uniforme**.
- O raio dessa trajetória circular é obtido igualando a força magnética à força centrípeta:
$$r = \frac{m \cdot v}{|q| \cdot B}$$
 onde $m$ é a massa da partícula.
- Esse princípio é a base de funcionamento de equipamentos como o **espectrômetro de massa** e os **aceleradores de partículas**, que utilizam campos magnéticos para curvar e separar partículas conforme sua razão carga/massa.

## 4. Força Magnética sobre um Fio Condutor (Força de Ampère)

- Um fio retilíneo de comprimento $L$, percorrido por uma corrente elétrica $i$, imerso em um campo magnético uniforme $\vec{B}$, sofre uma força magnética de intensidade:
$$F = B \cdot i \cdot L \cdot \text{sen}(\theta)$$
 onde $\theta$ é o ângulo entre a direção da corrente no fio e o campo magnético.
- Assim como na Força de Lorentz, a força é **máxima** quando o fio é perpendicular ao campo magnético, e **nula** quando o fio é paralelo a ele.
- A direção e o sentido dessa força também são determinados pela **regra da mão direita**, aplicada ao sentido convencional da corrente elétrica.

## 5. Campo Magnético Criado por Correntes Elétricas

Toda corrente elétrica gera, ao seu redor, um campo magnético próprio. As três configurações clássicas estudadas são:

- **Fio retilíneo longo:** o campo magnético forma círculos concêntricos ao redor do fio, com intensidade:
$$B = \frac{\mu_0 \cdot i}{2\pi \cdot d}$$
 onde $\mu_0$ é a permeabilidade magnética do meio (do vácuo, na maioria dos exercícios) e $d$ é a distância ao fio.
- **Espira circular:** no centro de uma espira circular de raio $R$ percorrida por corrente $i$, o campo magnético tem intensidade:
$$B = \frac{\mu_0 \cdot i}{2R}$$
- **Solenoide (bobina longa):** no interior de um solenoide de comprimento $L$ com $N$ espiras, o campo magnético é considerado **uniforme**, com intensidade:
$$B = \frac{\mu_0 \cdot N \cdot i}{L}$$
- Em todos os três casos, a direção do campo criado é determinada pela **regra da mão direita**, adaptada à geometria específica de cada configuração (envolvendo o fio com os dedos, por exemplo, no caso do fio retilíneo).

## 6. Indução Eletromagnética e a Lei de Faraday

- **Indução eletromagnética** é o fenômeno pelo qual a **variação do fluxo magnético** através de um circuito gera uma **força eletromotriz induzida** (e, consequentemente, uma corrente induzida, caso o circuito seja fechado).
- O **fluxo magnético** ($\Phi$) através de uma superfície de área $A$, em um campo magnético uniforme $B$, é dado por:
$$\Phi = B \cdot A \cdot \cos(\theta)$$
 onde $\theta$ é o ângulo entre o campo magnético e a normal à superfície.
- **Lei de Faraday:** a força eletromotriz induzida ($\varepsilon$) é proporcional à **taxa de variação do fluxo magnético** ao longo do tempo:
$$\varepsilon = -\frac{\Delta \Phi}{\Delta t}$$
- É importante notar que a indução ocorre sempre que o fluxo magnético **varia** — seja pela variação do campo magnético, da área do circuito, ou do ângulo entre eles —, e **não** pela simples presença de um campo magnético constante.

## 7. Lei de Lenz

- A **Lei de Lenz** determina o **sentido** da corrente elétrica induzida (representada pelo sinal negativo na Lei de Faraday): a corrente induzida sempre flui em um sentido tal que o campo magnético por ela criado **se opõe** à variação do fluxo magnético que a originou.
- Essa lei é, em essência, uma manifestação do **Princípio da Conservação de Energia** aplicado ao eletromagnetismo: se a corrente induzida reforçasse (em vez de se opor a) a variação do fluxo, o sistema geraria energia continuamente do nada, violando a conservação de energia.

## 8. Matriz Comparativa: Fontes de Campo Magnético por Corrente

| Configuração | Fórmula do campo magnético | Onde o campo é medido | Comportamento |
|---|---|---|---|
| **Fio retilíneo longo** | $B = \dfrac{\mu_0 \cdot i}{2\pi d}$ | A uma distância $d$ do fio | Diminui com o inverso da distância; linhas circulares concêntricas |
| **Espira circular** | $B = \dfrac{\mu_0 \cdot i}{2R}$ | No centro da espira | Depende do raio da espira; campo mais concentrado no centro |
| **Solenoide** | $B = \dfrac{\mu_0 \cdot N \cdot i}{L}$ | No interior do solenoide | Aproximadamente uniforme; depende do número de espiras por unidade de comprimento |

> [!quote] Strategic Counterpoint
> * **Erros Clássicos:**
> - Achar que a força magnética pode **acelerar ou desacelerar** uma partícula (alterar o módulo de sua velocidade) — como ela é sempre perpendicular à velocidade, a força magnética **nunca realiza trabalho**; ela apenas curva a trajetória, jamais altera a energia cinética da partícula.
> - Aplicar a Lei de Faraday/Lenz em situações de **campo magnético constante e circuito parado** — sem variação de fluxo magnético, não há força eletromotriz induzida, independentemente da intensidade do campo presente.
> - Confundir as **linhas de campo magnético** com as **linhas de campo elétrico**: as magnéticas são sempre curvas **fechadas** (saem do polo norte e retornam ao polo sul, inclusive dentro do próprio ímã), enquanto as elétricas se originam em cargas positivas e terminam em cargas negativas (ou no infinito), sem formar circuitos fechados.
>
> * **Distinção Crítica:**
> - **Força de Lorentz** vs. **Força de Ampère:** a Força de Lorentz ($F = qvB\,\text{sen}\,\theta$) atua sobre uma **carga elétrica pontual em movimento**; a Força de Ampère ($F = BiL\,\text{sen}\,\theta$) atua sobre um **fio condutor** percorrido por corrente, imerso em campo magnético. Na prática, a Força de Ampère é a **soma coletiva** das forças de Lorentz atuando sobre todos os portadores de carga em movimento dentro do fio — não são fenômenos diferentes, mas sim a mesma força física aplicada em duas escalas de análise distintas (carga individual vs. condutor macroscópico).
>
> * **Aplicação Prática:**
> - O par **motor elétrico / gerador elétrico** ilustra perfeitamente a relação de mão dupla entre os fenômenos estudados nesta nota: um **motor** usa a Força de Ampère sobre uma espira percorrida por corrente, imersa em um campo magnético, para converter energia elétrica em movimento rotacional; um **gerador** faz exatamente o processo inverso, girando mecanicamente uma espira dentro de um campo magnético para, por indução eletromagnética (Lei de Faraday), gerar uma corrente elétrica — é assim que usinas hidrelétricas, eólicas e termelétricas convertem energia mecânica em energia elétrica na prática.

---

Tags: [[Física]] [[Eletromagnetismo]] [[Magnetismo]]
