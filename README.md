<h1>VMD de Fortaleza</h1>

Projeto feito durante a cadeira de Big Data em Python, utiliza um dataset sobre o Volume Médio Diário (VMD) em Fortaleza, capturado pelos equipamentos de Fiscalização Eletrônica a partir de janeiro de 2017. Com base na análise desses dados através do algoritimo de <i>Machine Learning</i>, nosso objetivo é prever o VMD em diferentes vias, a fim de tomar medidas preventivas contra o congestionamento. 

<h2>Como Funciona ?🤔 </h2>
Tratamos os dados separando os em 2 partes:(Longitude, Latidude, Ano, Mês) - (VMD).Após isso, treinamos o algoritimo de <i>Machine Learning</i>, nesse caso o que obtemos maior precisão foi o de <i>Random Forest</i>, com base nisso o código prevê possiveís VMD.

<h2>Resultados ✅</h2>
O código tem um precisão de 0.95
<img src="https://github.com/Rua-N/VMD-de-Fortaleza/assets/106121054/39f19ac5-d765-4a24-923a-39161ecbc7cd">


<h2>Observação</h2>
O código foi feito através do Google Colab, caso tente rodar o código por alguma IDE ira ter que instalar os modulos manualmente. No caso do sklearn é (pip install -U scikit-learn).
