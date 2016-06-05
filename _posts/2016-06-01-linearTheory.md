---
title:  "Linear Theory of waves - Still in portuguese - english comming soon!"
author: Uggo Pinho
excerpt: "Linear Theory of water waves."
categories:
  - Science
tags:
  - theory
comments: true
---

## Linear theory of water waves

Apesar da complexidade das ondas no oceano, a partir de considerações relacionadas ao comportamento e propriedades das ondas, a teoria linear fornece uma solução para a equação de movimento para ondas de gravidade superficiais (Eq. \\eqref{eq:EqMov}) e ainda, por esta teoria são obtidas equações para a maior parte das propriedades cinemáticas e dinâmicas para ondas de gravidade superficiais para a maioria das circunstâncias práticas.

A equação de movimento para as ondas superficiais de gravidade inclui os termos de inércia, gradiente de pressão e força gravitacional:

\\begin{equation} \\label{eq:EqMov}
\\rho\\frac{d\\mathbf{V}}{dt}=-\\mathbf{\\nabla}{p}+\\rho\\mathbf{g}
\\end{equation}

onde \\(\\rho\\) é a densidade da água, \\( \\mathbf{V} \\) é o vetor velocidade das partículas, \\(t\\) é o tempo, \\(p\\) a pressão e
 \\( \\mathbf{g} \\) a gravidade. Assim, o termo do lado esquerdo é o termo de inércia, o primeiro termo do lado direito (\\(\\mathbf{\\nabla}{p}\\)) é relativo ao gradiente de pressão e o segundo à força gravitacional.

A teoria de pequena amplitude para onda de gravidade bidimensional, livre, periódica é desenvolvida linearizando a equação que define a condição de contorno de superfície livre. Com isto e a condição de contorno de fundo, uma velocidade potencial periódica é buscada que satisfaça a condição de fluxo irrotacional. Esta velocidade potencial é então utilizada para derivar as equações para varias características de ondas (isto é, celeridade da onda, velocidade e aceleração das partículas, pressão)\\cite{Sor:1978}. Especificamente, as considerações requeridas para o seu desenvolvimento são:

1. A água é homogênea, incompressível, e as forças das tenções superficiais são desprezíveis. Assim não há ondas de gravidade
internas ondas de pressão afetando o fluxo, e as ondas superficiais consideradas são maiores que as ondas onde os efeitos
capilares são importantes (isto é, ondas com compriment os de onda maiores que aproximadamente 1,7).

2. O fluxo é irrotacional. Assim, não há tenção cisalhante na interface ar-mar ou no fundo. Ondas sobre o efeito do vento (sendo geradas ou dissipadas) não são consideradas e o fluido desliza livremente sobre o fundo e sobre outras superfícies sólidas. Assim a velocidade potencial deve existir e satisfaz a equação de Laplace:

\\[
\\frac{\\partial ^{2}\\phi }{\\partial x^{2}}+\\frac{\\partial ^{2}\\phi }{\\partial
y^{2}}=0\\]

que é uma expressão de continuidade para fluxo irrotacional.

3. O fundo não está se movendo e é impermeável e horizontal. Portanto, não está adicionando nem retirando energia do fluxo ou refletindo energia da onda.

4. A pressão ao longo da interface ar-mar é constante. Assim não existe pressão do vento e diferenças de pressões hidrostáticas devido a diferenças de elevação da superfície são desprezíveis.

5. A amplitude de onda é pequena comparada ao comprimento e a profundidade local. Uma vez que as velocidades das partículas estão relacionadas à amplitude da onda, e a celeridade da onda (velocidade de fase) está relacionada à profundidade local e ao comprimento de onda, isto implica que as velocidades das partículas são pequenas quando comparadas com a celeridade da onda. Esta consideração, a mais restritiva, significa que a teoria linear de ondas é muito limitada em águas rasas e nas proximidades da zona de quebra, onde as velocidades das partículas na crista e no cavado se aproximam da velocidade de fase.


\\[
\\eta =\\frac{H}{2}\\cos 2\\pi (\\frac{x}{L}-\\frac{t}{T})
\\]

ou

\\begin{equation} \\label{eq:EqSor2.2}
\\eta =\\frac{H}{2}\\cos (kx-\\sigma t)
\\end{equation}

onde

\\[
k=\\frac{2\\pi }{L}
\\qquad \\textrm{(número de onda)}
\\]

\\[
\\sigma =\\frac{2\\pi }{T} \\qquad \\textrm{(freqüência ângular)}
\\]

Uma onda monocromática pode ser representada por uma senóide. Esta move-se com celeridade \\( C \\) em uma determinada profundidade \\(
d \\) em um sistema de coordenadas \\( x \\), \\( y \\) sendo respectivamente o eixo horizontal e vertical. A altura de onda é \\( H \\) (duas vezes a amplitude da onda) e seu comprimento \\( L\\). O período da onda, \\( T \\), está relacionado ao comprimento de onda \\( L \\) e à celeridade por \\( C=L/T \\).

No desenvolvimento da teoria linear obtém-se como resultado para a velocidade potencial \\( \\phi  \\):

\\begin{equation} \\label{eq:EqSor2.10}
\\phi =\\frac{H}{2}\\frac{g\\cosh k(d+y)}{\\sigma \\cosh kd}\\sin (kx-\\sigma t)
\\end{equation}


Outro resultado importante é a chamada relação de dispersão para águas profundas, que relaciona a freqüência angular \\( \\sigma \\) ao
número de ondas \\( k \\)

\\begin{equation} \\label{eq:EqSor2.11}
\\sigma ^{2}gk\\tanh (kd)
\\end{equation}

como
\\[
\\frac{\\sigma }{k}=\\frac{L}{T}=C
\\]

tem-se
\\begin{equation} \\label{eq:EqSor2.12}
C=\\sqrt{\\frac{gL}{2\\pi }\\tanh \\left( \\frac{2\\pi d}{L}\\right) }
\\end{equation}


Que é uma equação básica dando a celeridade da onda em função do comprimento de onda e a profundidade local. Nota-se que a celeridade da onda é independente da altura de onda pela teoria de pequena amplitude. A Eq. (\\eqref{eq:EqSor2.12}) pode ser escrita na forma

\\begin{equation} \\label{eq:EqSor2.13}
C=\\frac{gT}{2\\pi }\\tanh \\left( \\frac{2\\pi d}{L}\\right)
\\end{equation}

e

\\begin{equation} \\label{eq:EqSor2.14}
L=\\frac{gT^{2}}{2\\pi }\\tanh \\left( \\frac{2\\pi d}{L}\\right)
\\end{equation}

Esta última é uma equação transcendental, pois \\( L \\) está dos dois lados da equação, e pode ser resolvida numericamente.

Quando a onda se propaga de águas profundas em direção à costa seu comprimento, celeridade, altura, perfil, pressão interna e campo
de velocidades variam. O período da onda, porém, permanece constante.

### Classificação das Ondas com Relação à Profundidade Relativa}
\\label{sec:prof_rel}


Um sistema de classificação das ondas baseado na profundidade relativa (d/L) é mostrado na figura \\ref{fig:fig2.3sor}
\\footnote{ Tabelas como estas e de outras fun\\'{c}ões podem ser encontradas em \\cite{Wiegel:1964} e U.S. Army Coastal Engineering Research Center (1973). }.

\\begin{figure}[!hbt]
\\begin{center}
  \\includegraphics[width=0.70\\textwidth]{figuras/fig23sor.eps}
\\end{center}
\\caption{Vários parâmetros como uma função da profundidade relativa \\(d\\) (Fonte:\\cite{Sor:1978}).}\\label{fig:fig2.3sor} %fun\\'{c}ão
\\end{figure}

Quando a profundidade relativa é maior que aproximadamente 0.5, \\( \\tanh \\left( \\frac{2\\pi d}{L}\\right) \\cong 1.0 \\), e as equações (\\eqref{eq:EqSor2.11}) a (\\eqref{eq:EqSor2.14}), reduzem-se a:


\\begin{equation} \\label{eq:EqSor2.15}
C_{0}=\\sqrt{\\frac{gL_{0}}{2\\pi }}
\\end{equation}


\\begin{equation} \\label{eq:EqSor2.16}
C_{0}=\\frac{gT}{2\\pi }
\\end{equation}

e

\\begin{equation} \\label{eq:EqSor2.17}
L_{0}=\\frac{gT^{2}}{2\\pi }
\\end{equation}


Esta condição é chamada \\águas profundas\\ e é denotada por um zero subscrito. Em águas profundas, o movimento
das partículas decai com a profundidade tal que é aproximadamente zero em \\( d/L>0.5 \\). As características das ondas são independentes da profundidade como indicado nas equações(\\eqref{eq:EqSor2.15}) a  (\\eqref{eq:EqSor2.17}). Como se pode ver na figura \\ref{fig:fig2.3sor} , o erro percentual é pequeno em se assumir condições de águas profundas aplicadas para profundidades maiores do que um terço do comprimento de onda.

Quando a profundidade relativa é menor que cerca de 0.05, a \\(\\tanh \\left( \\frac{2\\pi d}{L}\\right) \\cong \\frac{2\\pi d}{L} \\) e a equação (\\eqref{eq:EqSor2.12}) torna-se\\footnote{ A teoria de ondas de pequena amplitude assume que a amplitude é pequena quando comparada com o comprimento de onda, o que não é sempre válido em águas rasas. Teoria de ondas de amplitudes finitas indicam que \\(
d\\textrm{ } \\)na  Eq . (\\eqref{eq:EqSor2.18}) deve ser substituído pela profundidade somada a amplitude de crista de onda quando a
amplitude é significativa quando comparada à profundidade. }


\\begin{equation} \\label{eq:EqSor2.18}
C=\\sqrt{gd}
\\end{equation}


A celeridade da onda é agora somente dependente da profundidade relativa, e o comprimento de onda e o período são relacionados por


\\[
L=\\sqrt{gd}T
\\]


Esta é a chamada condição de águas rasas. Lembrando que é a profundidade relativa que é importante nesta condição.

Para \\( 0.5>d/L>0.05 \\) a condição é intermediária e as equações (\\eqref{eq:EqSor2.12}) a (\\eqref{eq:EqSor2.14}) devem ser usadas.

Dividindo-se a equação (\\eqref{eq:EqSor2.13}) pela (\\eqref{eq:EqSor2.16}), ou  (\\eqref{eq:EqSor2.14})) pela (\\eqref{eq:EqSor2.17}) tem-se


\\begin{equation} \\label{eq:EqSor2.19}
\\frac{C}{C_{0}}=\\frac{L}{L_{0}}=\\tanh \\left( \\frac{2\\pi }{L}\\right)
\\end{equation}


que, quando comparadas na figura \\ref{fig:fig2.3sor} , indica um decréscimo na celeridade e no comprimento ocorrendo quando a onda se propaga de águas profundas para águas rasas. Como resultado de manipulação algébrica obtém-se


\\begin{equation} \\label{eq:EqSor2.20}
\\frac{d}{L}\\tanh \\left( \\frac{2\\pi }{L}\\right) =\\frac{d}{L_{0}}
\\end{equation}

que permite calcular o comprimento de onda em qualquer profundidade d, dado o comprimento de onda em águas profundas.
Valores de \\(d/L_{0}\\) como função de \\(d/L\\) são mostrados na figura \\ref{fig:fig2.3sor}


### Cinemática das Ondas e Pressão

Outro resultado importante gerado pela teoria linear é a componente vertical (\\(v\\)) e horizontal (\\(u\\)) da velocidade das
partículas de água. As componentes são dadas por

\\begin{equation} \\label{eq:EqSor2.21}
u=(\\frac{\\pi H}{T})\\left( \\frac{\\cosh k(d+y)}{\\sinh kd}\\right) \\cos
(kx-\\sigma t)
\\end{equation}

e

\\begin{equation} \\label{eq:EqSor2.22}
v=(\\frac{\\pi H}{T})\\left( \\frac{\\sinh k(d+y)}{\\sinh kd}\\right) \\sin (kx-\\sigma t)
\\end{equation}


Cada componente da velocidade é definida por uma equação constituída por três partes: (\\( 1^{\\underline{a}}\\)) a velocidade
da partícula na superfície, \\( \\pi H/T \\), (\\(2^{\\underline{a}}\\)) um termo hiperbólico definindo a modificação da velocidade da partícula com o aumento da profundidade relativa e a posição da partícula ao longo do eixo vertical, e (\\(
3^{\\underline{a}}\\)) um termo de fase dependente da posição e do instante no tempo. A distância \\( d+y \\) é medida do fundo até a
posição da partícula.

As seguintes relações são úteis para cálculos em cinemática de ondas como para obtenção da velocidade das partículas:

Águas profundas:

\\begin{equation} \\label{eq:EqSor2.27}
\\frac{\\cosh k(d+y)}{\\sinh kd}\\approx \\frac{\\sinh k(d+y)}{\\sinh kd}\\approx e^{ky}
\\end{equation}


Águas rasas:
\\begin{equation} \\label{eq:EqSor2.28}
\\frac{\\cosh k(d+y)}{\\sinh kd}\\approx \\frac{1}{kd}
\\end{equation}



\\begin{equation} \\label{eq:EqSor2.29}
\\frac{\\sinh k(d+y)}{\\sinh kd}\\approx 1+\\frac{y}{d}
\\end{equation}


Equação (\\eqref{eq:EqSor2.27}) indica que em águas profundas as velocidades das partículas (também aceleração e diâmetro da
órbita) decaem exponencialmente com o aumento da profundidade (distância da superfície a um ponto abaixo da superfície).

Substituindo as equações (\\eqref{eq:EqSor2.28})  e (\\eqref{eq:EqSor2.29}) nas equações (\\eqref{eq:EqSor2.21}) e
(\\eqref{eq:EqSor2.22}) e fazendo-se manipulações algébricas pode se obter as seguintes equações para águas rasas:


\\begin{equation} \\label{eq:EqSor2.30}
u=\\frac{H}{2}\\sqrt{\\frac{g}{d}}\\cos (kx-\\sigma t)
\\end{equation}


\\begin{equation} \\label{eq:EqSor2.31}
v=\\frac{\\pi H}{T}\\left( 1+\\frac{y}{d}\\right) \\sin (kx-\\sigma t)
\\end{equation}


As equações (\\eqref{eq:EqSor2.30}) e (\\eqref{eq:EqSor2.31}) indicam, que em águas rasas a componente horizontal da velocidade das
partículas é independente da distância abaixo do nível do mar (still level) e a componente vertical diminui de um máximo na superfície a zero no fundo.

Para a pressão, a seguinte expressão é obtida pela teoria de pequenas amplitudes:

\\begin{equation} \\label{eq:EqSor2.32}
p=-\\rho gy+\\frac{\\rho gH}{2}\\frac{\\cosh k(d+y)}{\\cosh kd}\\cos (kx-\\sigma t)
\\end{equation}


O primeiro termo do lado direito da equação é o termo de pressão hidrostática, o segundo é o relativo à pressão dinâmica devido à aceleração das partículas.

### Energia e Potência das Ondas


A energia total em uma onda é a soma da energia cinética, $E_{c}$, com a energia potencial, $E_{p}$. A Energia cinética por unidade
de largura de crista e para um determinado comprimento de onda é igual a integral no comprimento de onda e na profundidade de um
meio da massa de um elemento diferencial vezes a velocidade deste elemento ao quadrado. Assim


\\[
E_{c}=\\int_{0}^{L}\\int_{-d}^{0}\\frac{1}{2}\\rho dxdy(u^{2}+v^{2})
\\]


Colocando as equações (\\eqref{eq:EqSor2.21}) e (\\eqref{eq:EqSor2.22}) para as componentes das velocidades, integrando e manipulando algebricamente


\\[
E_{c}=\\frac{\\rho gH^{2}L}{16}
\\]


A energia potencial pode ser obtida a partir da equação:


\\[
E_{p}=\\int_{0}^{L}\\rho g(d+\\eta )\\left( \\frac{d+\\eta }{2}\\right) dx-\\rho gLd\\left( \\frac{d}{2}\\right)
\\]


A elevação da superfície como uma função de $x$ é dada pela equação (\\eqref{eq:EqSor2.2}) (sendo t=0). Fazendo-se os cálculos obtém-se:

\\[
E_{p}=\\frac{\\rho gH^{2}L}{16}\\]


Assim a energia cinética e a energia potencial são iguais e a energia total em uma onda por unidade de largura de crista é


\\begin{equation} \\label{eq:EqSor2.33}
E=E_{c}+E_{p}=\\frac{\\rho gH^{2}L}{8}
\\end{equation}


A energia é variável de um ponto para outro ao longo do comprimento de onda, mas a energia média por unidade de área superficial é

\\begin{equation} \\label{eq:EqSor2.34}
\\overline{E}=\\frac{E}{L}=\\frac{\\rho gH^{2}}{8}
\\end{equation}

Que é algumas vezes referida como densidade de energia ou energia específica.

A potência da onda é a energia da onda por unidade de tempo propagada na direção da onda. A potência pode ser escrita como o produto da força atuando em um plano vertical normal a propagação da onda vezes a velocidade do fluxo de partículas através deste plano. Por unidade de largura de crista, a potência média de onda é:

\\[
P=\\frac{1}{T}\\int_{0}^{T}\\int_{-d}^{0}(p+\\rho gy)udtdy
\\]


Aqui a força é a pressão dinâmica \\( p=\\rho gy \\) vezes a unidade de área na superfície, 1dy. Inserindo a pressão dinâmica de
(\\eqref{eq:EqSor2.32})  e a componente horizontal da velocidade da equação (\\eqref{eq:EqSor2.21}) e integrando, obtém-se


\\begin{equation} \\label{eq:EqSor2.35}
P=\\frac{\\rho gH^{2}L}{16T}\\left( 1+\\frac{2kd}{\\sinh 2kd}\\right)
\\end{equation}

ou


\\begin{equation} \\label{eq:EqSor2.36}
P=\\frac{E}{T}\\left[ \\frac{1}{2}\\left( 1+\\frac{2kd}{\\sinh 2kd}\\right) \\right]
\\end{equation}


Sendo


\\begin{equation} \\label{eq:EqSor2.37}
n=\\frac{1}{2}\\left( 1+\\frac{2kd}{\\sinh 2kd}\\right)
\\end{equation}


A equação (\\eqref{eq:EqSor2.36}) torna-se


\\begin{equation} \\label{eq:EqSor2.38}
P=\\frac{nE}{T}
\\end{equation}


A relação funcional entre o termo n e a profundidade relativa é indicada na figura \\ref{fig:fig2.3sor} , onde n aumenta de 0.5 em águas profundas a 1.0 em águas rasas. A equação (\\eqref{eq:EqSor2.38}) mostra que n pode ser pensado como sendo a fração da energia da onda que é transmitida na direção de propagação da onda.

Quando um trem de ondas se propaga, a energia por unidade de tempo passando em um ponto em seu caminho deve ser igual à energia por
unidade de tempo passando em um ponto subseqüente somada a energia refletida ou dissipada por unidade de tempo entre os dois pontos
entre os dois pontos. Se a taxa de reflexão e a de dissipação de energia são desprazíveis, a seguinte consideração é válida:


\\begin{equation} \\label{eq:EqSor2.39}
P=\\left(\\frac{nE}{T}\\right)_{1}=\\left(\\frac{nE}{T}\\right)_{2}=constante
\\end{equation}


A equação (\\eqref{eq:EqSor2.39}) indica, por exemplo, que quando um trem de ondas se propaga de águas profundas para águas rasas a energia no trem deve decrescer em uma taxa inversamente proporcional ao aumento de n, uma vez que o período da onda é constante.

Se forem feitas linhas normais, ou ortogonais, as cristas de uma onda quando um tem de ondas avança e assumindo que a energia de ondas se propaga ao longo das cristas de ondas (i.e. através das linhas ortogonais), a potência contida entre as ortogonais pode ser considerada constante. Se o espaçamento entre as ortogonais é denotado por B,


\\[
{\\left(\\frac{BnE}{T}\\right)\\}_{1}=\\left(\\frac{BnE}{T}\\right)}=constante
\\]


Inserindo a energia de onda pela equação (\\eqref{eq:EqSor2.33}) e reorganizando


\\begin{equation} \\label{eq:EqSor2.40}
\\frac{H_{1}}{H_{2}}=\\sqrt{\\frac{n_{2}L_{2}}{n_{1}L_{1}}}=\\sqrt{\\frac{B_{2}}{B_{1}}}
\\end{equation}


O primeiro termo do lado direito representa os efeitos de espraimento "shoaling" e o segundo termo os efeitos da divergência ou convergência das linhas ortogonais devido a refração de ondas. Estes são muitas vezes referidos como coeficientes de shoaling $K_{s}$ e de refração $K_{r}$ respectivamente. A variação da altura de onda de águas profundas para águas intermediárias ou águas rasas pode ser calculada pela equação (\\eqref{eq:EqSor2.40}) e é mostrada na figura \\ref{fig:fig2.3sor} na curva \\(\\frac{H}{H_{0}}\\). Inicialmente, quando a onda espraia (shoals) há um pequeno decréscimo na altura de onda pois $n$ aumenta em uma taxa mais rápida do que \\(L\\) diminui (ver equação (\\eqref{eq:EqSor2.35})) . Em profundidades relativas menores que aproximadamente 0.1 a altura de onda é maior que \\(H_{0}\\) e esta continua a aumentar até que a onda se torna instável e quebra.


### Celeridade do Grupo de Ondas

Quando o vento sopra sobre o mar transfere sua energia para a água gerando ondas com várias freqüências, e estas se propagam com uma
determinada celeridade que depende de seu período e da profundidade relativa (Eq.(\\eqref{eq:EqSor2.11})). Porém apenas uma fração $n$ de sua energia é transportada na direção de propagação. Este fenômeno é devido ao fato de que as ondas com freqüências próximas se propagam formando um grupo de ondas. A figura \\ref{fig:fig2.7sor} apresenta um esquema para um grupo de ondas formados por duas ondas monocromáticas superpostas com uma diferença entre seus comprimentos de ondas de $dL$ e diferença de celeridade de $dC$.

\\begin{figure}[!hbt]
\\begin{center}
  \\includegraphics[width=0.70\\textwidth]{figuras/fig27sor.eps}
\\end{center}
\\caption{Dois trens de ondas mostrados separadamente e superpostos (Fonte:\\cite{Sor:1978}).}\\label{fig:fig2.7sor}
\\end{figure}

Com relação à figura \\ref{fig:fig2.7sor} , o tempo necessário para o grupo de ondas se propagar a distância $dL$ é $dt$, onde $dt$ é igual a diferença entre os comprimentos de onda dividido pela diferença entre as celeridades das duas ondas. Assim

\\[
dt=\\frac{dL}{dC}
\\]

O grupo viaja uma distância $dx$ em um tempo $dt$, onde $dx$ é dado por

\\[
dx=\\left[ \\frac{(C+dC)+C}{2}\\right] - \\frac{(L+dL)+L}{2}\\approx Cdt-L
\\]

e

\\[
C_{g}=\\frac{dx}{dt}=\\frac{Cdt-L}{dt}=C-\\frac{L}{dt}
\\]

Como

\\[
dt=\\frac{dL}{dC}
\\]

então

\\begin{equation} \\label{eq:EqSor2.41}
C_{g}= C - L \\left( \\frac{dC}{dL}\\right)
\\end{equation}

Inserindo a Eq.(\\eqref{eq:EqSor2.12}) na Eq.(\\eqref{eq:EqSor2.41}) tem-se

\\begin{equation} \\label{eq:EqSor2.42}
C_{g}=\\frac{C}{2} \\left(1+ \\frac{2kd}{\\sinh 2kd }\\right)
\\end{equation}

ou

\\begin{equation} \\label{eq:EqSor2.43}
C_{g}=nC
\\end{equation}


O termo $n$ agora também define a razão entre a celeridade do grupo de ondas para a celeridade de fase. Relembrando que $n$ varia de 0.5 em águas profundas e 1 em águas rasas. Nota-se que a velocidade de propagação da energia de ondas é a mesma da celeridade do grupo de ondas.
