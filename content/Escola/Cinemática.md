Tags: [[física]] [[mecânica]]

> [!abstract]
> 
> A Cinemática estuda o movimento dos corpos sem investigar suas causas, utilizando as grandezas de espaço ($s$), tempo ($t$), velocidade ($v$) e aceleração ($a$). Compreende desde o repouso relativo até movimentos complexos como o lançamento oblíquo e o MCU, sendo a base para o estudo da Dinâmica e das leis de Newton.

## 1. Fundamentos: Referencial e Trajetória

O estado de movimento ou repouso de um corpo não é absoluto, mas dependente do sistema de coordenadas adotado.

- **Referencial:** Sistema em relação ao qual se observa o fenômeno; determina se há variação da posição no tempo.
    
- **Ponto Material vs. Corpo Extenso:** Um objeto é ponto material quando suas dimensões são desprezíveis em comparação com a escala do movimento estudado.
    
- **Espaço ($s$) e Deslocamento ($\Delta s$):**
    
    - $\Delta s = s_{final} - s_{inicial}$ (Vetor que liga o início ao fim).
        
    - Distância percorrida ($d$): Comprimento real da trajetória (sempre $\geq |\Delta s|$).
        

![difference between distance and displacement, gerada com IA|275](https://encrypted-tbn3.gstatic.com/licensed-image?q=tbn:ANd9GcTzRM6pYP0EuxyO5zxmfzBn0WH_y05WP8_NQek4Hd9jE0PLP4vIxR_jFf74Y4aYPqoBIBW1UE6GxV6hlA4iW--GNGx5kmS-wvkoclIfmIAwF-UcNnk)

## 2. Velocidade e Aceleração Escalar

Grandezas que medem a rapidez do movimento e a taxa de variação da velocidade.

- **Velocidade Média ($v_m$):** $v_m = \frac{\Delta s}{\Delta t}$
    
    _Contexto:_ Utilizada para a descrição global do percurso. No SI, a unidade é $m/s$.
    
- **Velocidade Instantânea:** O valor da velocidade em um instante específico ($t \to 0$).
    
- **Aceleração Média ($a_m$):** $a_m = \frac{\Delta v}{\Delta t}$
    
    _Contexto:_ Mede o quão rápido a velocidade do móvel aumenta ou diminui.
    
- **Conversão Crucial:** $1 \text{ m/s} = 3,6 \text{ km/h}$.
    

## 3. Movimento Uniforme (MU)

Movimento onde a velocidade escalar é constante e a aceleração é nula ($a = 0$).

- **Função Horária da Posição:** $s = s_0 + v \cdot t$
    
    _Contexto:_ Permite prever a posição do móvel em qualquer instante. O gráfico $s \times t$ é uma reta inclinada.
    
- **Velocidade Relativa ($v_{rel}$):**
    
    - Sentidos Opostos (Aproximação ou Afastamento): $v_{rel} = |v_A| + |v_B|$.
        
    - Mesmo Sentido: $v_{rel} = |v_A - v_B|$.
        

![position vs time graph for uniform motion, gerada com IA](https://encrypted-tbn2.gstatic.com/licensed-image?q=tbn:ANd9GcTe4F3-fhzuy8bLyh9kkbxBHERfHNMJiDGeikeI1c2TE_6KBxRA6b1ew526chF-ggC3nBJ1EoVnenbV_Cp5lUfj2bSk0gDiCwYt54tbpOWjQzDcfAc)

## 4. Movimento Uniformemente Variado (MUV)

Aceleração constante e diferente de zero ($a \neq 0$), alterando a velocidade de forma linear.

- **Função Horária da Velocidade:** $v = v_0 + a \cdot t$
    
- **Função Horária da Posição:** $s = s_0 + v_0 \cdot t + \frac{a \cdot t^2}{2}$
    
- **Equação de Torricelli:** $v^2 = v_0^2 + 2 \cdot a \cdot \Delta s$
    
    _Uso:_ Fundamental quando o enunciado não fornece e não solicita o tempo.
    
- **Classificação do Movimento:**
    
    - **Acelerado:** $|v|$ aumenta no tempo ($v$ e $a$ têm o mesmo sinal).
        
    - **Retardado:** $|v|$ diminui no tempo ($v$ e $a$ têm sinais opostos).
        
- **Propriedade Gráfica:** No gráfico $v \times t$, a **área** sob a reta representa o deslocamento ($\Delta s$).
    

## 5. Movimento Vertical e Lançamentos

Aplicação do MUV sob influência da gravidade ($g \approx 10 \text{ m/s}^2$).

- **Queda Livre:** Móvel abandonado do repouso ($v_0 = 0$). O tempo de queda é $t = \sqrt{\frac{2h}{g}}$.
    
- **Lançamento Vertical:** Movimento simétrico; o tempo de subida é igual ao de descida, e a velocidade no ponto de altura máxima é nula ($v = 0$).
    
- **Lançamento Oblíquo:** Decomposição vetorial em dois eixos independentes:
    
    - **Eixo X (Horizontal):** MU $\rightarrow v_x = v_0 \cdot \cos(\theta)$.
        
    - **Eixo Y (Vertical):** MUV $\rightarrow v_{0y} = v_0 \cdot \text{sen}(\theta)$.
        
    - **Alcance Máximo:** Ocorre quando o ângulo de lançamento é $45^{\circ}$.
        

## 6. Cinemática Vetorial e MCU

Estudo dos movimentos considerando a direção e o sentido das grandezas.

- **Vetor Velocidade ($\vec{v}$):** Sempre tangente à trajetória e aponta no sentido do movimento.
    
- **Aceleração Vetorial ($\vec{a}$):** Composta por duas componentes:
    
    1. **Tangencial ($\vec{a}_t$):** Altera o **módulo** da velocidade (existe se o movimento for variado).
        
    2. **Centrípeta ($\vec{a}_{cp}$):** Altera a **direção** da velocidade. Aponta para o centro da curva. $a_{cp} = \frac{v^2}{R}$.
        
- **Movimento Circular Uniforme (MCU):** Possui $\vec{a}_t = 0$, mas $\vec{a}_{cp} \neq 0$.
    
    - **Velocidade Angular ($\omega$):** $\omega = \frac{2\pi}{T} = 2\pi f$. Unidade: $rad/s$.
        
    - **Relação Linear-Angular:** $v = \omega \cdot R$ e $a_{cp} = \omega^2 \cdot R$.
        

> [!quote] Strategic Counterpoint
> 
> **Erros Clássicos:** No ENEM e UEPG, muitos alunos erram ao não converter as unidades para o SI antes de aplicar as fórmulas (ex: km/h para m/s). Outro erro fatal é usar Torricelli em movimentos circulares sem considerar a aceleração centrípeta.
> 
> **Distinção Crítica:** Velocidade escalar média ($d/t$) é diferente de velocidade vetorial média ($\Delta s / t$). No percurso de ida e volta ao mesmo ponto, o deslocamento é zero, logo a velocidade vetorial média é zero, mas a escalar média não.
> 
> **Aplicação Prática:** A aceleração centrípeta explica por que sentimos uma força nos "empurrando" para fora em curvas de carro (inércia) e é o princípio das centrífugas laboratoriais.

---

[[física]] [[vetores]] [[mecânica]] [[matemática básica]]