Tags: [[Física]] [[Óptica]] [[Óptica Geométrica]] [[Espelhos]]

> [!abstract]
> Espelhos são superfícies capazes de refletir a luz de forma **regular (especular)**, formando imagens de objetos. A Óptica Geométrica classifica os espelhos em **planos**, cuja superfície refletora é uma reta (em corte transversal), e **esféricos**, cuja superfície refletora é uma calota de esfera, subdividida em **côncava** (refletindo pela parte interna da calota) e **convexa** (refletindo pela parte externa). Enquanto o espelho plano sempre forma imagens **virtuais, direitas e do mesmo tamanho** do objeto, os espelhos esféricos formam imagens cujas características — reais ou virtuais, direitas ou invertidas, ampliadas ou reduzidas — dependem diretamente da posição do objeto em relação ao **foco** e ao **centro de curvatura** do espelho. Essas relações são descritas matematicamente pela **Equação de Gauss** e pela **equação do aumento linear transversal**, ferramentas centrais para prever com precisão onde e como uma imagem se formará, sustentando aplicações práticas que vão de espelhos retrovisores a telescópios refletores.

## 1. Espelhos Planos

- Um **espelho plano** é uma superfície refletora plana e polida.
- A imagem formada por um espelho plano é sempre:
 - **Virtual** (formada pelo prolongamento dos raios refletidos, e não pelo encontro real deles);
 - **Direita** (não invertida em relação ao objeto);
 - **Do mesmo tamanho** do objeto (aumento igual a 1);
 - Simétrica ao objeto em relação ao plano do espelho — a distância da imagem ao espelho é sempre igual à distância do objeto ao espelho.
- **Campo visual** de um espelho plano: é a região do espaço na qual um observador consegue enxergar sua própria imagem ou a de outros objetos refletidos, delimitada pela reflexão dos raios que partem das bordas do espelho.
- **Associação de espelhos planos:** quando dois espelhos planos são associados formando um ângulo entre si, o número de imagens formadas depende do ângulo $\theta$ entre eles:
$$N = \frac{360°}{\theta} - 1$$

## 2. Elementos dos Espelhos Esféricos

- **Centro de curvatura (C):** centro da esfera que originou a calota esférica do espelho.
- **Vértice (V):** ponto central da superfície refletora do espelho.
- **Eixo principal:** reta que passa pelo centro de curvatura e pelo vértice do espelho.
- **Raio de curvatura (R):** distância entre o centro de curvatura e o vértice.
- **Foco principal (F):** ponto do eixo principal onde convergem (ou de onde parecem divergir) os raios de luz paralelos ao eixo principal após a reflexão; localiza-se exatamente no ponto médio entre o vértice e o centro de curvatura:
$$f = \frac{R}{2}$$

## 3. Espelhos Côncavos e Convexos

- **Espelho côncavo:** reflete a luz pela parte interna da calota esférica; possui **foco real** (os raios refletidos efetivamente se cruzam no foco). É capaz de formar tanto imagens reais quanto virtuais, dependendo da posição do objeto.
- **Espelho convexo:** reflete a luz pela parte externa da calota esférica; possui **foco virtual** (apenas o prolongamento dos raios refletidos se encontra no foco, atrás do espelho). Forma **sempre** imagens virtuais, direitas e reduzidas, independentemente da posição do objeto.
- **Convenção de sinais** usual (referencial de Gauss): distâncias medidas do lado real (onde a luz efetivamente incide e se reflete) são positivas; distâncias medidas do lado virtual (atrás do espelho) são negativas. Nessa convenção, o espelho côncavo tem $f > 0$ e o convexo tem $f < 0$.

## 4. Construção Geométrica de Imagens: Raios Notáveis

Para determinar graficamente a posição e as características de uma imagem em um espelho esférico, utilizam-se raios de luz com trajetórias conhecidas:

- Um raio que incide **paralelo ao eixo principal** reflete passando pelo **foco** (no côncavo) ou parecendo partir do foco virtual (no convexo).
- Um raio que incide passando pelo **foco** reflete **paralelo ao eixo principal**.
- Um raio que incide passando pelo **centro de curvatura** reflete sobre si mesmo, no mesmo caminho (pois incide perpendicularmente à superfície).
- Um raio que incide sobre o **vértice** reflete formando com o eixo principal um ângulo igual ao de incidência (segue a Lei da Reflexão comum).

## 5. Equação de Gauss e Equação do Aumento Linear

- A **Equação de Gauss** relaciona a distância focal ($f$), a distância do objeto ao espelho ($p$) e a distância da imagem ao espelho ($p'$):
$$\frac{1}{f} = \frac{1}{p} + \frac{1}{p'}$$
- A **equação do aumento linear transversal** relaciona o tamanho da imagem ($i$) com o tamanho do objeto ($o$), e também pode ser calculada pelas distâncias $p$ e $p'$:
$$A = \frac{i}{o} = -\frac{p'}{p}$$
- Interpretação dos sinais de $A$: se $A > 0$, a imagem é **direita** (virtual, no caso de espelhos); se $A < 0$, a imagem é **invertida** (real); se $|A| > 1$, a imagem é **ampliada**; se $|A| < 1$, a imagem é **reduzida**.

## 6. Casos de Formação de Imagem no Espelho Côncavo

A posição do objeto em relação ao centro de curvatura (C) e ao foco (F) determina completamente as características da imagem formada:

- **Objeto além do centro de curvatura:** imagem real, invertida e reduzida, formada entre o foco e o centro.
- **Objeto exatamente no centro de curvatura:** imagem real, invertida e do mesmo tamanho, formada também no centro de curvatura.
- **Objeto entre o centro de curvatura e o foco:** imagem real, invertida e ampliada, formada além do centro de curvatura.
- **Objeto exatamente no foco:** os raios refletidos saem paralelos entre si, e a imagem se forma no infinito (não há formação de imagem finita).
- **Objeto entre o foco e o vértice:** imagem virtual, direita e ampliada, formada atrás do espelho.

## 7. Matriz Comparativa: Espelho Côncavo vs. Espelho Convexo

| Aspecto | Espelho Côncavo | Espelho Convexo |
|---|---|---|
| **Superfície refletora** | Parte interna da calota | Parte externa da calota |
| **Tipo de foco** | Real ($f > 0$) | Virtual ($f < 0$) |
| **Tipo(s) de imagem possível** | Real ou virtual, dependendo da posição do objeto | Sempre virtual, direita e reduzida |
| **Comportamento dos raios paralelos** | Convergem no foco | Divergem, parecendo partir do foco virtual |
| **Aplicação típica** | Faróis de carro, espelhos de dentista, antenas parabólicas, telescópios refletores | Espelhos retrovisores, espelhos de segurança em lojas e estacionamentos |

> [!quote] Strategic Counterpoint
> * **Erros Clássicos:**
> - Achar que espelhos **convexos** podem, em alguma situação, formar imagens reais ou ampliadas — isso nunca ocorre: independentemente da posição do objeto, o espelho convexo forma **sempre** imagem virtual, direita e reduzida.
> - Trocar os sinais na Equação de Gauss ou na equação do aumento, esquecendo que a convenção de sinais (positivo para o lado real, negativo para o lado virtual) muda o sinal de $f$ conforme o tipo de espelho (côncavo positivo, convexo negativo).
> - Confundir o **foco** com o **centro de curvatura** ao aplicar os raios notáveis — são pontos diferentes ($f = R/2$), e usar um no lugar do outro na construção geométrica leva a uma imagem incorretamente posicionada.
>
> * **Distinção Crítica:**
> - **Imagem Real** vs. **Imagem Virtual:** a imagem real é formada pelo **encontro efetivo** dos raios de luz refletidos, podendo ser projetada em um anteparo (como uma tela ou papel) — ocorre apenas em espelhos côncavos, quando o objeto está além do foco. A imagem virtual é formada pelo **prolongamento imaginário** dos raios refletidos, não podendo ser captada em um anteparo — ocorre em espelhos convexos (sempre) e em espelhos côncavos quando o objeto está entre o foco e o vértice.
>
> * **Aplicação Prática:**
> - Os espelhos retrovisores convexos são utilizados propositalmente por ampliarem o campo de visão do motorista (mostrando uma área maior, ainda que com objetos reduzidos), enquanto os espelhos côncavos são aplicados em faróis de veículos e em antenas parabólicas justamente pela capacidade de **concentrar** raios paralelos em um único ponto focal — o inverso também é usado: uma fonte de luz colocada no foco de um espelho côncavo emerge como um feixe de luz paralelo, princípio por trás do funcionamento dos faróis.

---

Tags: [[Física]] [[Óptica]] [[Óptica Geométrica]] [[Espelhos]]
