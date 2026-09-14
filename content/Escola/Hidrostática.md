Tags: [[Física]] [[Mecânica dos Fluidos]] [[Hidrostática]]

> [!abstract]
> A Hidrostática é o ramo da Física que estuda o comportamento dos **fluidos em repouso**, analisando como a pressão se distribui em seu interior e como ela interage com corpos submersos ou parcialmente imersos. O conceito central da disciplina é a **pressão**, definida como a razão entre uma força e a área sobre a qual ela é aplicada, e sua variação com a profundidade é descrita pelo **Teorema de Stevin**. A partir desse fundamento, três princípios clássicos organizam praticamente toda a Hidrostática aplicada: o **Princípio de Pascal**, que explica a transmissão integral da pressão em fluidos confinados e sustenta o funcionamento de prensas e freios hidráulicos; o **Princípio de Arquimedes**, que explica por que corpos flutuam ou afundam por meio do **empuxo**; e o estudo dos **vasos comunicantes** e da **pressão atmosférica**, que explicam fenômenos que vão do nível da água em recipientes ligados até o funcionamento de barômetros.

## 1. Conceitos Fundamentais

- **Fluido:** substância capaz de escoar e se adaptar à forma do recipiente que a contém, categoria que engloba líquidos e gases.
- **Densidade (massa específica):** razão entre a massa de uma substância e o volume que ela ocupa:
$$\rho = \frac{m}{V}$$
- **Pressão:** razão entre a intensidade de uma força aplicada perpendicularmente a uma superfície e a área dessa superfície:
$$P = \frac{F}{A}$$
 A unidade de pressão no Sistema Internacional é o **Pascal (Pa)**, equivalente a 1 N/m².

## 2. Pressão Hidrostática e o Teorema de Stevin

- A **pressão hidrostática** é a pressão exercida pelo próprio peso de uma coluna de fluido em um determinado ponto, e depende exclusivamente da **densidade do fluido** e da **profundidade** — não depende do formato ou do volume total do recipiente.
- **Teorema de Stevin:** a diferença de pressão entre dois pontos de um mesmo fluido em equilíbrio é proporcional à diferença de profundidade entre eles:
$$\Delta P = \rho \cdot g \cdot \Delta h$$
 onde $\rho$ é a densidade do fluido, $g$ é a aceleração da gravidade e $\Delta h$ é a diferença de profundidade entre os pontos.
- A **pressão absoluta** em um ponto de um fluido, considerando também a pressão exercida pela atmosfera sobre a superfície livre do fluido, é dada por:
$$P_{\text{abs}} = P_{\text{atm}} + \rho \cdot g \cdot h$$

## 3. Princípio de Pascal

- **Enunciado:** um acréscimo de pressão aplicado em um ponto de um fluido em equilíbrio, confinado em um recipiente fechado, se transmite **integralmente** a todos os demais pontos do fluido.
- Esse princípio fundamenta o funcionamento das **prensas hidráulicas**, nas quais uma pequena força aplicada em um êmbolo de área pequena gera uma força muito maior em um êmbolo de área grande, conectados pelo mesmo fluido:
$$\frac{F_1}{A_1} = \frac{F_2}{A_2}$$
- Esse sistema **não viola a conservação de energia**: o ganho de força é compensado por uma perda proporcional de deslocamento — o êmbolo maior se move uma distância proporcionalmente menor que o êmbolo pequeno.

## 4. Princípio de Arquimedes e Empuxo

- **Enunciado:** todo corpo total ou parcialmente imerso em um fluido em equilíbrio recebe, da parte do fluido, uma força vertical, de baixo para cima, chamada **empuxo**, de intensidade igual ao peso do volume de fluido deslocado pelo corpo.
- Fórmula do empuxo:
$$E = \rho_{\text{fluido}} \cdot g \cdot V_{\text{deslocado}}$$
- **Condições de flutuação**, comparando o empuxo com o peso do corpo:
 - Se $E > P$ (peso do corpo): o corpo sobe até que parte dele emerja e o sistema atinja equilíbrio (corpo flutua);
 - Se $E = P$: o corpo permanece em equilíbrio, totalmente submerso, em qualquer profundidade;
 - Se $E < P$: o corpo afunda.
- Um corpo flutua na superfície de um líquido quando sua **densidade média é menor** que a densidade do líquido — é por isso que um navio de aço, com formato adequado para deslocar um grande volume de água, consegue flutuar mesmo sendo feito de um material mais denso que a água.

## 5. Vasos Comunicantes

- Quando dois ou mais recipientes estão ligados entre si na base, formando um sistema de **vasos comunicantes**, um mesmo líquido em equilíbrio atinge o **mesmo nível** em todos os ramos, independentemente do formato ou da largura de cada um deles — desde que estejam sujeitos à mesma pressão externa.
- Quando líquidos de densidades diferentes e não miscíveis são colocados em vasos comunicantes, as alturas das colunas de cada líquido, medidas a partir da superfície de separação entre eles, são **inversamente proporcionais às suas densidades**:
$$\rho_1 \cdot h_1 = \rho_2 \cdot h_2$$

## 6. Pressão Atmosférica

- A atmosfera terrestre exerce pressão sobre todos os corpos e superfícies devido ao peso da coluna de ar acima deles.
- O primeiro a medir experimentalmente a pressão atmosférica foi **Evangelista Torricelli**, em 1643, por meio de um tubo de vidro preenchido com mercúrio e invertido em uma cuba do mesmo líquido — o experimento demonstrou que, ao nível do mar, a pressão atmosférica sustenta uma coluna de mercúrio de aproximadamente **760 mmHg**, valor equivalente a **1 atm** ou aproximadamente **101.325 Pa**.
- A pressão atmosférica **diminui com a altitude**, pois a coluna de ar acima do ponto de medição se torna progressivamente menor.

## 7. Matriz Comparativa dos Princípios da Hidrostática

| Princípio | O que descreve | Fórmula central | Aplicação típica |
|---|---|---|---|
| **Teorema de Stevin** | Variação da pressão com a profundidade em um fluido | $\Delta P = \rho \cdot g \cdot \Delta h$ | Cálculo de pressão em diferentes profundidades (mar, represas) |
| **Princípio de Pascal** | Transmissão integral de um acréscimo de pressão em fluido confinado | $F_1/A_1 = F_2/A_2$ | Prensas hidráulicas, freios hidráulicos, elevadores de carro |
| **Princípio de Arquimedes** | Força de empuxo sobre corpos imersos em fluido | $E = \rho_{\text{fluido}} \cdot g \cdot V_{\text{deslocado}}$ | Flutuação de navios, submarinos, balões, densímetros |

> [!quote] Strategic Counterpoint
> * **Erros Clássicos:**
> - Achar que a **pressão hidrostática** depende do **volume total** de líquido no recipiente ou de sua largura — na verdade, ela depende exclusivamente da **profundidade** e da **densidade do fluido**, sendo igual em pontos de mesma profundidade mesmo em recipientes de formatos completamente diferentes (o chamado "paradoxo hidrostático").
> - Calcular o empuxo usando a densidade do **corpo** em vez da densidade do **fluido** — a fórmula do empuxo depende apenas da densidade do fluido deslocado e do volume deslocado, nunca da densidade do objeto imerso.
> - Confundir **pressão absoluta** com **pressão manométrica** (relativa à atmosfera) — muitos instrumentos de medição (como calibradores de pneu) indicam a pressão manométrica, que é a pressão absoluta descontada a pressão atmosférica.
>
> * **Distinção Crítica:**
> - **Empuxo** vs. **Peso Aparente:** o empuxo é a força que o fluido exerce sobre o corpo imerso, sempre para cima; o **peso aparente** é o resultado da subtração entre o peso real do corpo e o empuxo recebido — é o peso aparente, e não o peso real, que um dinamômetro mede ao pesar um objeto submerso em um líquido: $P_{\text{aparente}} = P_{\text{real}} - E$.
>
> * **Aplicação Prática:**
> - O Princípio de Arquimedes é usado no projeto de **navios e submarinos**: os navios têm casco oco para maximizar o volume de água deslocado e reduzir sua densidade média abaixo da densidade da água; os submarinos controlam ativamente sua densidade média enchendo ou esvaziando tanques de lastro com água, permitindo submergir, flutuar ou manter profundidade constante conforme a necessidade operacional.

---

Tags: [[Física]] [[Mecânica dos Fluidos]] [[Hidrostática]]
