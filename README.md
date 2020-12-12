# fgv-timeseries

## Introdução:
O agronegócio desempenha um importante papel na geração de riqueza no Brasil. Nas últimas décadas, o setor conviveu com inovações em produção e a Empresa Brasileira de Pesquisa Agropecuária – EMBRAPA, tem um papel relevante neste processo. 
O agronegócio efetua anualmente elevados investimentos que retroalimenta toda uma gama de cadeias econômicas, além de contribuir com uma maior eficiência e eficácia na produção de alimentos. Neste quesito, o consumo de fertilizantes ocupa uma parcela signiﬁcativa dos investimentos realizados.

##	Base de Dados: 
Os dados do arquivo anexado “Demanda.xlsx” contempla a entrega de fertilizantes ao mercado em mil toneladas no período mensal de janeiro de 1998 a abril de 2020.  
A fonte dos dados é o sítio da Associação Nacional para Difusão de Adubos –ANDA (http://anda.org.br/estatisticas/).

##	O trabalho individual: 
O trabalho individual deverá ser entregue sob a forma de um relatório em Word (ou pdf) ou sob a forma de uma apresentação em ppt, lembrando que o ideal seja na forma de uma “story telling”. 

As etapas a serem cumpridas são: 

* Um breve comentário inicial relacionado à análise exploratória dos dados, incluindo a visualização, identificação de padrões, decomposição e o entendimento do padrão da série. 

* Considerar os seguintes subconjuntos de dados:
    Intervalo de janeiro/2007 até dezembro/ 2018 para modelagem da série temporal para treinamento (train).
    intervalo de janeiro/2019 até abril/2020 será base para testar o modelo (test).

* Selecionar os modelos de estudo: 
i.	Holt-Winters Aditivo 
ii.	Holt_Winters Multiplicativo
iii.	Modelo SARIMA(p,d,q)(P,D,Q)[s].

d.	Plotar os correlogramas ACF e PACF e verificar a estacionariedade da série temporal. 

e.	Efetuar os testes de raíz-unitária: Augmented Dickey_Fuller, Kwiatkowski–Phillips–Schmidt–Shin (KPSS) e Phillip-Perron.

f.	Modelagem do SARIMA(p,d,q)(P,D,Q)[s].

g.	 Os parâmetros do modelo são estatisticamente significativos? Efetuar o t-test() do pacote BETS.

h.	Efetuar os testes de diagnósticos para o modelo SARIMA(p,d,q)(P,D,Q)[s] (Ausência de autocorrelação serial; ausência de heterocedasticidade condicional; normalidade).
i.	Qual é o melhor modelo? Justifique.

j.	Com base no melhor modelo, efetuar a previsão com base no subconjunto de treinamento (train) para o período até dezembro-2021. Comparar com as demandas com a base teste.

k.	Conclusão sucinta.

IV.	Data-limite para entrega do trabalho: 10-12-20.
