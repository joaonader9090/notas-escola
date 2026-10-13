Tags: [[Física]] [[Física Moderna]] [[Física Nuclear]]

> [!abstract]
> A Física Nuclear estuda o **núcleo atômico**, a região minúscula e extremamente densa que concentra praticamente toda a massa do átomo e é formada por **prótons** e **nêutrons**, conhecidos em conjunto como **núcleons**. Como os prótons se repelem eletricamente, a coesão do núcleo só é possível graças à **força nuclear forte**, atrativa e de curtíssimo alcance, e a energia que mantém o núcleo unido corresponde à massa "perdida" na sua formação, o **defeito de massa**, conforme a equivalência $E = mc^2$. Núcleos instáveis tendem a se transformar espontaneamente emitindo partículas ou ondas eletromagnéticas, fenômeno chamado de **radioatividade**, que obedece a uma lei estatística de **decaimento exponencial** caracterizada pela **meia-vida**. Núcleos também podem ser modificados em reações provocadas: a **fissão** (divisão de núcleos pesados) alimenta usinas e armas, e a **fusão** (união de núcleos leves) é a fonte de energia das estrelas. As aplicações vão da **medicina nuclear** e da **datação por carbono-14** à geração de eletricidade, mas exigem rigor no controle dos riscos da radiação ionizante.

## 1. Estrutura do Núcleo Atômico

- O núcleo tem dimensão da ordem de 10⁻¹⁵ m (um **femtômetro**), cerca de cem mil vezes menor que o átomo, mas concentra mais de 99,9% de sua massa.
- Cada núcleo é caracterizado por dois números:
 - **Número atômico ($Z$):** quantidade de prótons, que define o elemento químico;
 - **Número de massa ($A$):** soma de prótons e nêutrons, ou seja, $A = Z + N$.
- A notação usual de um nuclídeo é ${}^{A}_{Z}\text{X}$, e a comparação entre nuclídeos usa três termos:
 - **Isótopos:** mesmo $Z$, diferente $A$ (ex: carbono-12 e carbono-14);
 - **Isóbaros:** mesmo $A$, diferente $Z$;
 - **Isótonos:** mesmo número de nêutrons, diferentes $Z$ e $A$.
- Na escala nuclear, a repulsão elétrica entre prótons é vencida pela **força nuclear forte**, que atua apenas a distâncias muito curtas (da ordem de 1 a 3 femtômetros) e atrai tanto prótons quanto nêutrons.
- Em núcleos mais pesados, é necessário um número de nêutrons maior que o de prótons para manter a estabilidade, e **nenhum núcleo com $Z$ acima de 83 (bismuto)** é completamente estável.

## 2. Energia de Ligação e Estabilidade

- A massa de um núcleo é **menor** que a soma das massas de seus núcleons isolados; essa diferença é o **defeito de massa**:
$$\Delta m = \left( Z \, m_p + N \, m_n \right) - m_{\text{núcleo}}$$
- A **energia de ligação** é a energia equivalente a esse defeito, ou seja, a energia necessária para separar completamente o núcleo em seus núcleons:
$$E_{\text{lig}} = \Delta m \cdot c^2$$
- Na escala nuclear, a unidade prática de energia é o **elétron-volt**, com 1 MeV equivalente a um milhão de elétrons-volt, e a massa é expressa em **unidade de massa atômica**, em que 1 u equivale a cerca de 931,5 MeV/c².
- O indicador de estabilidade é a **energia de ligação por núcleon**, que cresce até a região do **ferro-56** (em torno de 8,8 MeV por núcleon) e depois diminui lentamente para núcleos mais pesados.
- Essa curva explica por que há liberação de energia tanto na **fusão** de núcleos leves quanto na **fissão** de núcleos pesados: ambas levam a núcleos mais próximos do máximo de estabilidade.

## 3. Radioatividade e Tipos de Emissão

- A **radioatividade** foi descoberta por **Henri Becquerel** (1896) em sais de urânio e estudada em profundidade por **Marie e Pierre Curie**, que isolaram o polônio e o rádio.
- Núcleos instáveis emitem radiação até atingirem uma configuração estável, em três formas principais:
 - **Radiação alfa ($\alpha$):** núcleo de hélio-4 (2 prótons e 2 nêutrons); o núcleo emissor perde 2 unidades de $Z$ e 4 de $A$:
$${}^{A}_{Z}\text{X} \rightarrow {}^{A-4}_{Z-2}\text{Y} + {}^{4}_{2}\alpha$$
 - **Radiação beta menos ($\beta^-$):** elétron emitido quando um nêutron se converte em próton (junto com um antineutrino); $Z$ aumenta em 1 e $A$ permanece:
$${}^{A}_{Z}\text{X} \rightarrow {}^{A}_{Z+1}\text{Y} + {}^{0}_{-1}\beta + \bar{\nu}$$
 - **Radiação gama ($\gamma$):** fóton de alta energia emitido na desexcitação de um núcleo, **sem alterar** $Z$ nem $A$.
- Há ainda o decaimento **beta mais**, em que um próton se converte em nêutron com emissão de um pósitron, reduzindo $Z$ em 1.
- Essas regras de conservação de $Z$ e de $A$ nas equações nucleares são conhecidas como **leis de Soddy e Fajans** (para alfa e beta).
- Os tipos de radiação diferem muito em **poder de penetração**: a alfa é barrada por uma folha de papel, a beta por uma lâmina fina de alumínio, e a gama exige blindagens espessas de chumbo ou concreto.

## 4. Lei do Decaimento Radioativo e Meia-Vida

- O decaimento de um núcleo individual é **imprevisível**, mas em uma grande amostra a fração que decai por unidade de tempo é constante, resultando em um decaimento **exponencial**:
$$N(t) = N_0 \cdot e^{-\lambda t}$$
 onde $\lambda$ é a **constante de decaimento**, característica de cada nuclídeo.
- A **meia-vida** ($T$) é o tempo necessário para que metade dos núcleos radioativos de uma amostra decaia, e se relaciona com $\lambda$ por:
$$T = \frac{\ln 2}{\lambda}$$
- Em termos de meias-vidas, a quantidade restante após um tempo $t$ é:
$$N(t) = N_0 \left( \frac{1}{2} \right)^{t/T}$$
 Após 1 meia-vida resta 50% da amostra, após 2 resta 25%, e após 3 resta 12,5%.
- A **atividade** de uma amostra, número de decaimentos por segundo, é dada por $A = \lambda N$ e medida em **becquerel (Bq)**, em que 1 Bq equivale a 1 decaimento por segundo.
- Exemplos de meias-vidas: o **tecnécio-99m** tem cerca de 6 horas, o **iodo-131** cerca de 8 dias, o **césio-137** cerca de 30 anos e o **carbono-14** cerca de 5.730 anos.
- O **carbono-14** permite a **datação** de materiais orgânicos de até dezenas de milhares de anos: seres vivos mantêm uma proporção constante de C-14, e após a morte essa proporção cai segundo a lei de decaimento.

## 5. Fissão Nuclear

- A **fissão** é a divisão de um núcleo pesado em dois núcleos menores, com liberação de nêutrons e de grande quantidade de energia. Foi descoberta em 1938 por **Otto Hahn** e **Fritz Strassmann** e interpretada por **Lise Meitner** e Otto Frisch.
- Uma reação típica, com o urânio-235 atingido por um nêutron, é:
$${}^{235}_{92}\text{U} + {}^{1}_{0}\text{n} \rightarrow {}^{141}_{56}\text{Ba} + {}^{92}_{36}\text{Kr} + 3\,{}^{1}_{0}\text{n} + \text{energia}$$
 A energia liberada é de cerca de 200 MeV por fissão, milhões de vezes maior, por átomo, que a de uma reação química.
- Os nêutrons liberados podem provocar novas fissões, o que gera uma **reação em cadeia**; para que ela se sustente é necessária uma **massa crítica** de material físsil.
- Em um **reator nuclear** de potência, como os das usinas de Angra dos Reis, a reação é controlada por:
 - **Moderador** (por exemplo, água), que desacelera os nêutrons para aumentar a chance de novas fissões;
 - **Barras de controle** (boro ou cádmio), que absorvem nêutrons e regulam a taxa de reação;
 - **Refrigerante**, que retira o calor para produzir vapor e acionar turbinas.
- O urânio natural contém apenas cerca de 0,7% de U-235, e por isso é **enriquecido** (poucos por cento para reatores, mais de 90% para armas).
- O principal problema da fissão é o **rejeito radioativo** de longa duração, que exige armazenamento seguro por milhares de anos.

## 6. Fusão Nuclear

- A **fusão** é a união de dois núcleos leves em um núcleo mais pesado, com liberação de energia, desde que o produto esteja abaixo do ferro na curva de energia de ligação.
- Exemplo de reação de interesse para reatores futuros, entre os isótopos de hidrogênio deutério e trítio:
$${}^{2}_{1}\text{H} + {}^{3}_{1}\text{H} \rightarrow {}^{4}_{2}\text{He} + {}^{1}_{0}\text{n} + 17{,}6 \text{ MeV}$$
- É o processo que alimenta o **Sol**, onde, no balanço total, quatro núcleos de hidrogênio se fundem em um de hélio-4, liberando cerca de 26,7 MeV.
- A fusão exige **temperaturas de milhões de graus** (no núcleo do Sol, cerca de 15 milhões de °C) para que os núcleos vençam a repulsão elétrica e se aproximem a ponto de a força forte atuar.
- Na Terra, o desafio tecnológico é **confinar** esse gás superaquecido (plasma), seja por campos magnéticos (reatores tipo **tokamak**, como o ITER) ou por compressão a laser; ainda não há usinas de fusão comerciais.
- Por unidade de massa de combustível, a fusão libera mais energia que a fissão e gera rejeitos de vida muito mais curta, mas a **bomba de hidrogênio** mostra o outro lado do processo, quando não controlado.

## 7. Radiação, Efeitos Biológicos e Aplicações

- As radiações alfa, beta, gama, além dos raios X, são **ionizantes**: têm energia suficiente para arrancar elétrons de átomos e danificar moléculas das células, como o DNA.
- Três grandezas são usadas para quantificar o assunto:
 - **Atividade** (Bq): quantos decaimentos por segundo ocorrem em uma fonte;
 - **Dose absorvida** (gray, Gy): energia absorvida por quilograma de matéria, 1 Gy equivalente a 1 J/kg;
 - **Dose equivalente** (sievert, Sv): corrige a dose absorvida pelo poder de dano de cada tipo de radiação, sendo a medida usada para estimar o risco biológico.
- Aplicações médicas e científicas:
 - **Diagnóstico:** radiofármacos como o tecnécio-99m, e a tomografia **PET**, que usa emissores de pósitrons;
 - **Tratamento:** radioterapia com cobalto-60 ou aceleradores para destruir tumores, e iodo-131 para doenças da tireoide;
 - **Outras áreas:** datação por carbono-14, esterilização de materiais hospitalares e irradiação de alimentos para conservação.
- Acidentes nucleares relevantes mostram a importância do controle: **Chernobyl** (1986), **Fukushima** (2011) e, no Brasil, o acidente com **césio-137 em Goiânia** (1987), causado pela violação de uma fonte radioterápica abandonada.

## 8. Matrizes Comparativas

### 8.1 Radiações Alfa, Beta e Gama

| Aspecto | Alfa ($\alpha$) | Beta ($\beta^-$) | Gama ($\gamma$) |
|---|---|---|---|
| **Natureza** | Núcleo de hélio-4 | Elétron de origem nuclear | Onda eletromagnética de alta energia |
| **Carga** | Positiva | Negativa | Nula |
| **Alteração no núcleo** | $Z$ diminui 2 e $A$ diminui 4 | $Z$ aumenta 1; $A$ igual | Nenhuma em $Z$ e $A$ |
| **Poder de penetração** | Baixo (barrada por papel e pele) | Médio (barrada por lâmina de alumínio) | Alto (exige chumbo ou concreto) |
| **Poder ionizante** | Alto | Médio | Baixo |

### 8.2 Fissão vs. Fusão

| Aspecto | Fissão | Fusão |
|---|---|---|
| **Processo** | Divisão de núcleo pesado | União de núcleos leves |
| **Combustível típico** | Urânio-235, plutônio-239 | Deutério e trítio (isótopos de hidrogênio) |
| **Condições necessárias** | Massa crítica e nêutrons | Temperaturas de milhões de graus e confinamento |
| **Onde ocorre** | Usinas e armas atômicas | Estrelas, como o Sol; bomba H; reatores experimentais |
| **Rejeitos** | Radioativos de longa duração | Pouca radioatividade de vida longa |
| **Estágio tecnológico** | Dominado comercialmente | Experimental |

> [!quote] Strategic Counterpoint
> * **Erros Clássicos:**
> - Achar que, após **duas meias-vidas**, toda a amostra terá decaído: restam 25% do material, e a cada meia-vida a quantidade é reduzida **pela metade**, nunca a zero em tempo finito.
> - Confundir a energia de uma reação **nuclear** com a de uma reação **química**: a primeira é medida em MeV e a segunda em poucos eV por átomo, uma diferença de cerca de um milhão de vezes.
> - Achar que um reator de usina pode explodir como uma bomba atômica: o combustível é pouco enriquecido e a geometria é incompatível com uma explosão nuclear, embora acidentes graves (superaquecimento, explosões de vapor ou hidrogênio) sejam possíveis.
> - Esquecer que, nas equações nucleares, **tanto $Z$ quanto $A$ se conservam** entre os dois lados da seta, e tentar "fechar" a conta modificando só um deles.
>
> * **Distinção Crítica:**
> - **Irradiação** vs. **contaminação radioativa:** na irradiação, a pessoa ou objeto é **exposto** à radiação emitida por uma fonte externa (como em uma radiografia ou radioterapia) e **não se torna radioativo**; na contaminação, o material radioativo entra em contato ou é ingerido, ficando sobre ou dentro do corpo e continuando a irradiar. O acidente de Goiânia foi um caso de contaminação, o que explica a gravidade dos efeitos.
>
> * **Aplicação Prática:**
> - A **medicina nuclear** usa traçadores de meia-vida curta (como o tecnécio-99m, de cerca de 6 horas) justamente para permitir exames de imagem com dose baixa e rápido desaparecimento da radioatividade do corpo, enquanto o carbono-14 funciona como "relógio" arqueológico, aplicando diretamente a lei do decaimento para estimar a idade de fósseis e artefatos.

---

Tags: [[Física]] [[Física Moderna]] [[Física Nuclear]]
