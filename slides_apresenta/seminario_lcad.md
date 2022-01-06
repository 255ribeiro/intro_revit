---
marp: true
theme: gaia
size: 14:10 
paginate: true
header: "| 2022"
footer: "Fernando Ferraz Ribeiro | ffribeiro@gmail.com"


---

<!-- _header: "" -->
<!-- _footer: "" -->
<!-- _paginate: false -->
<!-- _backgroundImage: url('img/covers/BG_CICLES8.png') -->
<!-- _class: invert lead -->

<h1 style="text-shadow: -5px 5px #555555ff; margin: 0px; padding: 0px; font-size: 40px; color: white">Seminário LCAD 2021:</h1>
<br>
<h2 style="background-color: #88888877; margin: 0px; padding: 10px; font-size: 50px; color: white;">Análise de dados aplicada ao planejamento e gestão das cidades</h2>

<h1 style="margin: 0px; padding: 0px; font-size: 40px; text-shadow: -5px 5px #555555ff; color: white;transform: translate(0%, 25%);">Fernando Ferraz Ribeiro</h1>


---
<!-- _class: lead -->
<!-- _backgroundColor: white -->

<img src="./img/tags.gif" alt="Machine Learning" style="transform: scale(.5) translate(0%, -2%);">



---
<!-- _class: lead invert-->


<p style="font-size: 2.2rem; font-weight: bolder;text-align: justify; text-justify: inter-word;">"(...) the use of different techniques to measure the correlation with smart cities data and the exploitation of correlations to infer new knowledge are still open questions. (...) Furthermore, cities need to derive innovative solutions that can automatically infer urban dynamics and therefore to provide crucial information to urban planners."</p>

<p style="font-size: 1.5rem"> Bermudez-Edo, M., Barnaghi, P., & Moessner, K. (2018). <a href"https://doi.org/10.1016/j.autcon.2017.12.036" target="_blank">Analysing real world data streams with spatio-temporal correlations: Entropy vs. Pearson correlation.</a> Automation in Construction, 88, 87–100.</p>

---
<!-- _class: lead -->
<!-- _backgroundColor: white -->

# Análise de dados da Covid-19

Análise exploratória

Relatório Defensoria pública do Mato grosso do Sul

[servidor pythonaywhere](http://ffribeiro.pythonanywhere.com/)


---
<!-- _class: lead invert-->


# Projeto de tese

## Um modelo de aprendizado de máquina baseado no DMCx² aplicado à análise de dados espaço-temporais dos fluxos urbanos.


---
<!-- _class: lead -->
<!-- _backgroundColor: white -->

<div style="float: left; width: 40%">
<h4 style= "color: black; text-align: center; font-size: 40px; margin: 0px;padding: 0px">Ciência de Dados</h4> 

<ul style="font-size: 24px; font-weight: bolder; text-align: justify">
<li>Engloba um conjunto de novas disciplinas.</li>
<li>Paradigma/abordagem guiado(a) por dados: gerar conhecimento através da análise de grandes conjuntos de dados.</li>
<li>Busca por padrões nos conjuntos de dados.</li>
<li>Que os padrões encontrados agreguem valor à(s) área(s) relacionadas com aquele dado.</li>

</ul>
</div>

<img style="position: absolute; bottom: 8%;
  right: 5%; width: 40%"   src=".\img\MAPA_conceitual_ciencia_de_dados_recorte.jpg">



---
<!-- _class: lead -->
# Objetivo:
Criar um algoritmo de aprendizado de máquina, baseado no DMCx² capaz de analisar dados espaço-temporais relativos aos fluxos urbanos de maneira eficiente, capazes de generalizar e gerar valor a partir dos dados de treinamento.

---
<!-- _class: lead -->
<!-- _backgroundColor: white -->

<img src=".\img\mat_est_ML.svg" alt="Machine Learning" style="transform: scale(.75) translate(0%, -2%);">

---
<!-- _class: lead invert-->

## Premissas:

<ol style="font-size: 30px; font-weight: bolder; text-align: justify">
<li>DMCx² é uma generalização do método <em>rho</em>DDCA para múltiplas séries temporais.</li>
<li>O <em>rho</em>DDCA, em determinadas condições testadas, apresentou resultados mais robustos do que os do coeficiente de Pearson.</li>
<li >A capacidade de generalização de um algoritmo de aprendizado de máquina tem, dentre outras coisas, ajudado a comunidade científica a compreender melhor fenômenos complexos e problemas fracamente definidos.</li>
<li >Pesquisadores da área de <em>smart cities</em> apontams a necessidade de se explorar novos métodos para a análise dos conjuntos de dados de interesse.</li>

</ol>

---
<!-- _class: lead -->
# Variáveis:
* DFA
* DCCA
* *P*DCCA
* DMCx²
* Algoritmos de aprendizado de máquina.
* Conjuntos de dados retratando diferentes fluxos urbanos.

---

<!-- _backgroundColor:  white -->

<div style="float: left; width: 45%">
<h4 style= "color: black; text-align: center; font-size: 35px; margin: 0px;padding: 0px">Diagrama de Grimm<br><span style="font-size: 25px">(1/2)</span></h4> 

<ol style="font-size: 22px; font-weight: bolder; text-align: justify">
<li>Pergunta: É possível avançar com as aplicações baseadas em dados no planejamento das cidades utilizando os coeficientes e métodos relacionados com o PDCCA?</li>
<li>Hipótese: É possível criar uma ferramenta de aprendizado de Máquina eficiente baseada no DMCx². </li>
<li style="color: #163571ff">Padrões esperados: que seja possível criar modelos preditivos baseados nos dados.</li>
<li style="color: #f51c0bff">Estrutura do modelo: Associar o DMCx² com um modelo de Aprendizado de máquina existente.</li>

</ol>
</div>


<img style="position: absolute; bottom: 15%;
  right: 2%; width: 50%"   src=".\img\Ciclo_Grimm.svg">


---
<!-- _backgroundColor:  white -->

<div  style="float: left; width: 45%">
<h4 style= "color: black; text-align: center; font-size: 35px; margin: 0px;padding: 0px">Diagrama de Grimm<br><span style="font-size: 25px">(2/2)</span></h4> 

<ol start="5" style="font-size: 22px; font-weight: bolder; text-align: justify">
<li>Implementação do modelo: Utilizando a linguagem de programação Python, uma das mais utilizadas na área de aprendizado de máquina, e um conjunto de bibliotecas adequado</li>
<li>Análise do Modelo: Utilizando conjuntos de dados de teste, treinamento e validação, métrica adequada ao problema, matriz de confusão (...)</li>
<li style="color: #163571ff">Padrões encontrados: (...)</li>
<li style="color: #a5a13eff;">Comunicação do modelo: Através de artigos científicos, aplicativos e pacotes de programação.</li>

</ol>

<img style="position: absolute; bottom: 15%;
  right: 2%; width: 50%"   src=".\img\Ciclo_Grimm.svg">


---
<!-- _class: invert lead -->

### Produtos
- Artigo: revisão de literatura
- Aplicativo de Cálculo do DMCx2
- Pacote Python para cálculo do DFA, DCCA *P*DCCA e DMCx2
- Artigo: revista [Software X](https://www.journals.elsevier.com/softwarex)
- Implementação do modelo de IA uando DMx2
- Artigo: validação do modelo IA
- Aplicação do modelo para avaliação de mobilidade urbana
- Artigo: análise de mobilidade urbana


---

<!-- _header: "" -->
<!-- _footer: "" -->
<!-- _backgroundColor: Teal -->
<!-- _class: invert lead -->


<h1 style="color: white;font-size: 70px; font-weight: 1000"> FIM </h1>
