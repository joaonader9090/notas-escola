Tags: [[Física]] [[Eletrodinâmica]] [[Eletromagnetismo]] [[Capacitores]]

> [!abstract]
> Um capacitor é um componente elétrico capaz de **armazenar energia** na forma de um campo elétrico, constituído por dois condutores (armaduras ou placas) separados por um material isolante, o **dielétrico**. Sua capacidade de armazenar carga elétrica para uma dada diferença de potencial é quantificada pela grandeza **capacitância**, medida em **Farads**, e depende exclusivamente das características geométricas do capacitor e do material dielétrico utilizado — nunca da carga ou da tensão aplicada em um dado momento. Quando capacitores são combinados em um circuito, seu comportamento em **associações série e paralelo** segue regras estruturalmente **opostas** às regras de associação de resistores, um ponto frequentemente confundido por quem já domina a Eletrodinâmica resistiva. Componentes centrais em circuitos eletrônicos modernos, os capacitores sustentam aplicações que vão do flash de câmeras fotográficas à memória volátil dos computadores (DRAM).

## 1. Definição e Função de um Capacitor

- Um **capacitor** é um dispositivo elétrico formado por dois condutores (chamados **armaduras** ou **placas**) separados por um material isolante, o **dielétrico**, cuja função é **armazenar energia elétrica** na forma de um campo elétrico estabelecido entre suas placas.
- Ao ser conectado a uma fonte de tensão, o capacitor acumula cargas elétricas de sinais opostos em cada uma de suas placas — uma placa acumula carga positiva e a outra, carga negativa de mesmo módulo.

## 2. Capacitância

- **Capacitância (C)** é a grandeza que mede a capacidade de um capacitor de armazenar carga elétrica para uma determinada diferença de potencial (tensão) aplicada entre suas placas:
$$C = \frac{Q}{U}$$
 onde $Q$ é o módulo da carga armazenada em cada placa e $U$ é a diferença de potencial entre as placas.
- A unidade de capacitância no Sistema Internacional é o **Farad (F)**; por ser uma unidade muito grande para a maioria das aplicações práticas, é comum o uso de submúltiplos como o microfarad ($\mu F$), o nanofarad ($nF$) e o picofarad ($pF$).
- A capacitância é uma propriedade **intrínseca** do capacitor — depende apenas de sua geometria e do material dielétrico utilizado, **não** da carga ou da tensão aplicada em um instante específico.

## 3. Capacitor de Placas Paralelas

- O modelo mais simples de capacitor é formado por duas placas condutoras planas e paralelas, separadas por uma distância $d$ e por um material dielétrico de permissividade $\varepsilon$.
- A capacitância desse tipo de capacitor é calculada por:
$$C = \frac{\varepsilon \cdot A}{d}$$
 onde $A$ é a área de cada placa, $d$ é a distância entre elas e $\varepsilon$ é a permissividade elétrica do material dielétrico entre as placas.
- Consequências diretas dessa fórmula: quanto **maior a área** das placas, maior a capacitância; quanto **maior a distância** entre elas, menor a capacitância; e quanto **maior a permissividade** do dielétrico utilizado, maior a capacitância.

## 4. Energia Armazenada em um Capacitor

- A energia potencial elétrica armazenada em um capacitor carregado pode ser calculada por qualquer uma das seguintes formas equivalentes, dependendo das grandezas conhecidas:
$$E = \frac{Q \cdot U}{2} = \frac{C \cdot U^2}{2} = \frac{Q^2}{2C}$$
- Essa energia corresponde à área sob o gráfico de tensão em função da carga armazenada durante o processo de carregamento do capacitor.

## 5. Associação de Capacitores em Série

- Em uma associação **série**, todos os capacitores são percorridos pela **mesma carga elétrica** $Q$, enquanto a tensão total da associação é a **soma das tensões** individuais em cada capacitor.
- A capacitância equivalente de uma associação em série é calculada pelo **inverso da soma dos inversos**:
$$\frac{1}{C_{eq}} = \frac{1}{C_1} + \frac{1}{C_2} + \frac{1}{C_3} + \dots$$
- Para apenas dois capacitores em série, é comum usar a forma direta:
$$C_{eq} = \frac{C_1 \cdot C_2}{C_1 + C_2}$$
- A capacitância equivalente de uma associação em série é sempre **menor** que a menor das capacitâncias individuais associadas.

## 6. Associação de Capacitores em Paralelo

- Em uma associação **paralela**, todos os capacitores estão submetidos à **mesma tensão** $U$, enquanto a carga total armazenada pela associação é a **soma das cargas** individuais em cada capacitor.
- A capacitância equivalente de uma associação em paralelo é simplesmente a **soma direta** das capacitâncias individuais:
$$C_{eq} = C_1 + C_2 + C_3 + \dots$$
- A capacitância equivalente de uma associação em paralelo é sempre **maior** que a maior das capacitâncias individuais associadas.

## 7. Processo de Carga e Descarga (Circuito RC)

- Quando um capacitor é conectado a uma fonte de tensão por meio de um resistor (formando um **circuito RC**), ele não se carrega instantaneamente: a carga e a tensão sobre suas placas crescem de forma exponencial ao longo do tempo até atingirem o valor máximo permitido pela fonte.
- De forma análoga, ao ser desconectado da fonte e ligado a um resistor, o capacitor se **descarrega** de forma exponencial, liberando gradualmente a energia armazenada.
- A velocidade desse processo é caracterizada pela **constante de tempo** do circuito, $\tau = R \cdot C$, que representa o tempo necessário para que a carga (ou a tensão) atinja aproximadamente 63% do seu valor final durante o carregamento (ou caia a 37% do valor inicial durante a descarga).

## 8. Matriz Comparativa: Associação Série vs. Paralelo

| Aspecto | Associação em Série | Associação em Paralelo |
|---|---|---|
| **Grandeza igual em todos os componentes** | Carga elétrica ($Q$) | Tensão ($U$) |
| **Grandeza que se soma** | Tensão total ($U_{total} = U_1 + U_2 + \dots$) | Carga total ($Q_{total} = Q_1 + Q_2 + \dots$) |
| **Cálculo da capacitância equivalente** | $\dfrac{1}{C_{eq}} = \dfrac{1}{C_1} + \dfrac{1}{C_2} + \dots$ | $C_{eq} = C_1 + C_2 + \dots$ |
| **Resultado em relação aos componentes individuais** | $C_{eq}$ é sempre **menor** que a menor capacitância da associação | $C_{eq}$ é sempre **maior** que a maior capacitância da associação |

> [!quote] Strategic Counterpoint
> * **Erros Clássicos:**
> - **Inverter as fórmulas de associação de capacitores com as de resistores** — quem já domina Eletrodinâmica resistiva tende a aplicar, por hábito, a fórmula de soma direta para capacitores em série (que é, na verdade, a fórmula de resistores em série) e a fórmula do inverso da soma para capacitores em paralelo (que é a fórmula de resistores em paralelo). É exatamente o oposto: capacitores em série somam inversos; capacitores em paralelo somam diretamente.
> - Achar que a **capacitância** de um capacitor muda quando ele é carregado ou descarregado — a capacitância é uma propriedade fixa, determinada pela geometria e pelo dielétrico; o que varia com a carga e a descarga são a **carga armazenada** e a **tensão**, não a capacitância.
> - Esquecer que, em uma associação **série**, a carga é igual em todos os capacitores, mas a **tensão se distribui de forma desigual** entre eles caso as capacitâncias sejam diferentes — capacitores de menor capacitância acumulam maior tensão na associação série.
>
> * **Distinção Crítica:**
> - **Associação Série de Capacitores** vs. **Associação Série de Resistores:** embora ambas usem o termo "série", o comportamento matemático é **invertido** entre os dois componentes. Em resistores, a série soma diretamente as resistências ($R_{eq} = R_1 + R_2 + \dots$) e o paralelo soma os inversos; em capacitores, ocorre exatamente o oposto — a série soma os inversos e o paralelo soma diretamente. Essa inversão decorre da natureza física distinta dos dois componentes: resistores dissipam energia continuamente ao longo da corrente, enquanto capacitores armazenam carga em suas placas.
>
> * **Aplicação Prática:**
> - Capacitores de alta capacitância são usados no **flash de câmeras fotográficas e smartphones**: eles se carregam lentamente a partir da bateria (corrente baixa) e liberam toda a energia armazenada quase instantaneamente no momento do disparo (corrente alta e breve), algo que a bateria sozinha não conseguiria fornecer com a mesma rapidez. Em outra escala, a **memória DRAM** dos computadores armazena cada bit de informação como a carga (ou ausência de carga) de um capacitor microscópico, exigindo atualização constante ("refresh") devido à descarga natural gradual desses capacitores ao longo do tempo.

---

Tags: [[Física]] [[Eletrodinâmica]] [[Eletromagnetismo]] [[Capacitores]]
