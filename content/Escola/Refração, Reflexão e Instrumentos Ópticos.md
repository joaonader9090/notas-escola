Tags: [[Física]] [[Óptica]] [[Óptica Geométrica]] [[Instrumentos Ópticos]]

> [!abstract]
> Esta nota aplica as leis da **reflexão** e da **refração** a situações concretas e mostra como, combinadas com espelhos e lentes, elas sustentam o funcionamento do **olho humano** e dos **instrumentos ópticos**. No campo da reflexão, o foco está nos efeitos de movimento de espelhos planos; na refração, nos casos em que a luz atravessa superfícies planas, como o **dioptro plano** (que explica a profundidade aparente), a **lâmina de faces paralelas** e o **prisma**, além de fenômenos naturais como a **miragem**, o **arco-íris** e a **reflexão total** em fibras ópticas. O olho humano funciona como um sistema convergente que forma imagem real na **retina**, e seus defeitos (**miopia**, **hipermetropia**, **presbiopia** e **astigmatismo**) são corrigidos com lentes cuja vergência é calculada pela equação de Gauss. Por fim, a **lupa**, a **câmera fotográfica**, o **projetor**, o **microscópio composto** e os telescópios (**refratores** e **refletores**) são entendidos como arranjos de lentes e espelhos, cuja eficácia é medida pela **ampliação**, linear ou angular, conforme o instrumento.

## 1. Reflexão: Aplicações com Espelhos Planos

- A reflexão segue a **Lei da Reflexão** (ângulo de incidência igual ao de reflexão, medidos em relação à normal), e a imagem de um objeto em um espelho plano é virtual, direita, do mesmo tamanho e simétrica ao objeto em relação ao plano do espelho (ver [[Espelhos]]).
- **Rotação do espelho:** se um espelho plano gira de um ângulo $\alpha$ em torno de um eixo no seu plano, mantendo-se fixo o raio incidente, o raio refletido gira de $2\alpha$.
- **Translação do espelho:** se um espelho plano se desloca com velocidade $v$ em relação a um objeto fixo, a imagem se desloca com velocidade $2v$.
- Os dois resultados são aplicados em instrumentos de medida de alta sensibilidade, como o **galvanômetro de espelho**, em que a pequena rotação é amplificada pela dobra do ângulo.

## 2. Refração: Revisão e Relações Entre Grandezas

- A **Lei de Snell-Descartes** relaciona os ângulos medidos em relação à normal com os índices de refração dos dois meios (ver [[Óptica Geométrica - Fundamentos e Bases]]):
$$n_1 \cdot \text{sen}\,\theta_1 = n_2 \cdot \text{sen}\,\theta_2$$
- Na refração, a **frequência** da onda luminosa é **constante**, determinada pela fonte; o que se altera ao mudar de meio são a **velocidade** e o **comprimento de onda**:
$$n = \frac{c}{v} = \frac{\lambda_0}{\lambda} \qquad \text{e portanto} \qquad \frac{\text{sen}\,\theta_1}{\text{sen}\,\theta_2} = \frac{v_1}{v_2} = \frac{\lambda_1}{\lambda_2}$$
- Ao passar para um meio mais refringente, a luz **diminui** de velocidade e de comprimento de onda e **se aproxima da normal**.
- O **ângulo limite** para reflexão total, quando a luz vai de um meio mais refringente ($n_1$) para um menos refringente ($n_2$), é dado por:
$$\text{sen}\,L = \frac{n_2}{n_1}$$

## 3. Dioptro Plano e Profundidade Aparente

- Um **dioptro plano** é a superfície plana de separação entre dois meios transparentes, como a superfície da água em uma piscina.
- Um observador que vê um objeto através do dioptro, em incidência quase perpendicular, enxerga uma **imagem virtual** a uma distância diferente da real, e as distâncias à superfície se relacionam por:
$$\frac{p'}{p} = \frac{n_{\text{observador}}}{n_{\text{objeto}}}$$
 onde $p$ é a profundidade real, $p'$ a profundidade aparente, e os índices correspondem ao meio em que está o observador e ao meio em que está o objeto.
- Para um peixe visto do ar ($n_{\text{ar}} \approx 1$, $n_{\text{água}} \approx 1{,}33$), a imagem aparece **mais próxima da superfície** que o peixe real, com $p' = p/1{,}33$.
- Pela mesma razão, uma piscina parece **mais rasa** do que é, e um objeto submerso parece estar **mais acima** do que realmente se encontra, o que causa erros de pontaria ao tentar pegar ou atingir algo dentro d'água.

## 4. Lâmina de Faces Paralelas e Prisma

- Em uma **lâmina de faces paralelas** (por exemplo, uma vidraça), o raio que emerge é **paralelo** ao raio incidente, mas sofre um **deslocamento lateral** $d$, que cresce com a espessura $e$ da lâmina:
$$d = \frac{e \cdot \text{sen}(\theta_1 - \theta_2)}{\cos\theta_2}$$
 onde $\theta_1$ é o ângulo de incidência e $\theta_2$ o de refração no interior da lâmina.
- Em um **prisma óptico** de ângulo de abertura $A$, o raio sofre duas refrações e se desvia em direção à base do prisma. Com $i$ e $i'$ os ângulos de incidência e emergência, e $r$ e $r'$ os de refração nas duas faces:
$$A = r + r' \qquad \text{e} \qquad \delta = i + i' - A$$
 O **desvio mínimo** ocorre quando o raio atravessa o prisma simetricamente ($i = i'$ e $r = r' = A/2$), resultando em $\delta_{\text{mín}} = 2i - A$.
- Como o índice de refração depende da cor, o prisma produz **dispersão**: o violeta, de menor comprimento de onda, é desviado mais que o vermelho.

## 5. Fenômenos Naturais e Tecnológicos

- **Miragem:** em estradas aquecidas, o ar junto ao solo é mais quente e menos denso, portanto de **menor índice de refração**; os raios vindos do céu se curvam gradualmente para cima, e o observador vê a "poça" como uma imagem invertida do céu.
- **Arco-íris:** a luz solar sofre refração e dispersão ao entrar em uma gota de água, reflexão interna no fundo da gota e nova refração ao sair. O vermelho aparece no arco externo (cerca de 42° em relação ao ponto oposto ao Sol) e o violeta no interno.
- **Brilho do diamante:** com índice de refração de cerca de 2,42, o ângulo limite do diamante é de aproximadamente 24°, valor baixo que favorece múltiplas reflexões totais internas, e é por isso que sua lapidação o faz brilhar tanto.
- **Fibra óptica:** o núcleo, de índice maior, é envolto por uma casca de índice menor, e o sinal luminoso segue por **reflexões totais sucessivas**, com perdas mínimas.

## 6. O Olho Humano e os Defeitos da Visão

- O olho funciona como um sistema convergente: a **córnea** e o **cristalino** formam, na **retina**, uma imagem **real, invertida e reduzida**, que o cérebro interpreta na posição correta.
- A **acomodação visual** é o ajuste do cristalino, feito pelos músculos ciliares, que alteram sua curvatura e, portanto, sua distância focal, para focalizar objetos a diferentes distâncias.
- No olho normal, o **ponto remoto** está no infinito e o **ponto próximo** fica a cerca de 25 cm.
- Os principais defeitos e suas correções são:
 - **Miopia:** o globo ocular é alongado ou o cristalino é muito convergente, e a imagem de objetos distantes forma-se **antes da retina**; o ponto remoto é finito e a correção usa **lente divergente**;
 - **Hipermetropia:** o globo é curto ou o cristalino é pouco convergente, e a imagem forma-se **depois da retina**; o ponto próximo é afastado e a correção usa **lente convergente**;
 - **Presbiopia (vista cansada):** perda de elasticidade do cristalino com a idade, que afasta o ponto próximo; corrigida com lente convergente, como na hipermetropia;
 - **Astigmatismo:** curvatura irregular da córnea, que impede a focalização nítida em um único plano; corrigido com **lente cilíndrica**.
- Para a **miopia**, a lente corretiva deve formar, a partir de um objeto no infinito, uma imagem no ponto remoto, de modo que sua distância focal tem módulo igual ao do ponto remoto $d_r$:
$$f = -d_r \qquad \text{e} \qquad V = \frac{1}{f}$$
 Por exemplo, um míope com ponto remoto de 50 cm precisa de $f = -0{,}5$ m, ou seja, **-2 dioptrias**.
- Para a **hipermetropia** ou presbiopia, a lente deve, a partir de um objeto a 25 cm, formar uma imagem virtual no ponto próximo $d_p$ do paciente, o que dá, pela equação de Gauss:
$$\frac{1}{f} = \frac{1}{0{,}25} - \frac{1}{d_p}$$
 Com $d_p = 1$ m, $1/f = 4 - 1 = 3$, ou seja, uma lente de **+3 dioptrias**.
- O "grau" de óculos é a **vergência** da lente em dioptrias (ver [[Lentes]]).

## 7. Instrumentos Ópticos

- **Câmera fotográfica:** uma lente convergente forma, no sensor, uma imagem **real, invertida e menor** que o objeto. A focalização é feita variando a distância entre a lente e o sensor (para objetos mais próximos, a lente se afasta), e o **diafragma** regula a quantidade de luz.
- **Projetor:** o slide é posto entre o foco e o dobro da distância focal da lente convergente, formando imagem **real, invertida e ampliada** na tela; por isso, o slide é inserido de cabeça para baixo.
- **Lupa:** lente convergente com o objeto entre o foco e o centro óptico, que fornece imagem **virtual, direita e ampliada**. Sua ampliação **angular** (em relação à visão sem instrumento, com $D = 25$ cm) é:
$$M = 1 + \frac{D}{f} \quad (\text{imagem no ponto próximo}) \qquad \text{ou} \qquad M = \frac{D}{f} \quad (\text{imagem no infinito})$$
- **Microscópio composto:** a **objetiva**, de distância focal muito curta, forma uma imagem real, invertida e ampliada, que a **ocular** (funcionando como lupa) amplia de novo. A imagem final é virtual e invertida em relação ao objeto, e a ampliação total é o produto das ampliações:
$$M_{\text{total}} = M_{\text{objetiva}} \cdot M_{\text{ocular}}$$
 Por exemplo, uma objetiva de 40× com ocular de 10× produz ampliação total de 400×.
- **Luneta astronômica (refrator):** a **objetiva**, de grande distância focal, forma a imagem real do astro distante, observada pela **ocular**, de distância focal curta. Para imagem final no infinito:
$$M = \frac{f_{\text{obj}}}{f_{\text{oc}}} \qquad \text{e} \qquad L \approx f_{\text{obj}} + f_{\text{oc}}$$
- **Telescópio refletor (tipo Newton):** substitui a lente objetiva por um **espelho côncavo**, o que elimina a aberração cromática e permite construir aberturas muito maiores, já que espelhos podem ser apoiados por trás.

## 8. Matrizes Comparativas

### 8.1 Defeitos da Visão

| Defeito | Causa principal | Onde se forma a imagem | Lente corretiva |
|---|---|---|---|
| **Miopia** | Globo alongado ou cristalino muito convergente | Antes da retina | Divergente (vergência negativa) |
| **Hipermetropia** | Globo curto ou cristalino pouco convergente | Depois da retina | Convergente (vergência positiva) |
| **Presbiopia** | Perda de elasticidade do cristalino | Depois da retina (visão de perto) | Convergente |
| **Astigmatismo** | Curvatura irregular da córnea | Focos diferentes em planos diferentes | Cilíndrica |

### 8.2 Instrumentos Ópticos

| Instrumento | Elementos | Imagem final | Característica central |
|---|---|---|---|
| **Câmera fotográfica** | Lente convergente, diafragma, sensor | Real, invertida, reduzida | Foco ajustado pela distância lente-sensor |
| **Projetor** | Lente convergente, slide | Real, invertida, ampliada | Objeto entre $f$ e $2f$ |
| **Lupa** | Uma lente convergente | Virtual, direita, ampliada | Objeto entre o foco e a lente |
| **Microscópio composto** | Objetiva e ocular convergentes | Virtual, invertida, muito ampliada | Ampliação = produto das duas |
| **Luneta astronômica** | Objetiva (f longa) e ocular (f curta) | Virtual, invertida | $M = f_{\text{obj}}/f_{\text{oc}}$ |
| **Telescópio refletor** | Espelho côncavo e ocular | Virtual, invertida | Sem aberração cromática |

> [!quote] Strategic Counterpoint
> * **Erros Clássicos:**
> - Achar que a **frequência** da luz muda ao refratar: ela é determinada pela fonte e permanece **constante**; o que muda são a velocidade e o comprimento de onda.
> - Inverter a razão na fórmula do dioptro plano e concluir que um objeto submerso parece estar **mais fundo**: visto do ar, ele parece **mais raso**, pois $p' = p \cdot n_{\text{observador}}/n_{\text{objeto}}$ resulta em valor menor.
> - Corrigir **miopia** com lente convergente (ou hipermetropia com divergente): o sinal da vergência acompanha o defeito, negativa para míopes e positiva para hipermétropes e presbitas.
> - Tratar a **ampliação da lupa** como a razão entre o tamanho da imagem e o do objeto: em instrumentos que o olho observa, o que importa é a razão entre os **ângulos** de visão com e sem o instrumento.
>
> * **Distinção Crítica:**
> - **Ampliação linear transversal** vs. **ampliação angular:** a linear compara o tamanho da imagem com o do objeto ($A = i/o = -p'/p$) e é a usada quando a imagem é projetada ou fotografada; a angular compara o ângulo sob o qual se vê a imagem com o ângulo sob o qual se veria o objeto a olho nu e é a adequada para **lupas, microscópios e lunetas**, cujas imagens são observadas diretamente. Uma luneta de ampliação angular 50× não produz imagem "50 vezes maior" em tamanho, e sim um objeto distante visto sob um ângulo 50 vezes maior.
>
> * **Aplicação Prática:**
> - A prescrição de **óculos e lentes de contato** é a aplicação direta do cálculo de vergência, enquanto os grandes **telescópios modernos** são todos refletores, como o James Webb, cujo espelho principal de 6,5 m é formado por 18 segmentos hexagonais, solução que seria impossível com uma lente de dimensão equivalente.

---

Tags: [[Física]] [[Óptica]] [[Óptica Geométrica]] [[Instrumentos Ópticos]]
