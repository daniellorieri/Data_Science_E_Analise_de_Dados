# Data_Science_E_Analise_de_Dados

Objetivo desta análise é tentar extrair insigth e  verificar quais indicadores com base em um setup usado que uso para operar mini-indíce futuro no gráfico intraday no tempo de 5min, no período de 02-08-2021 a 26-08-2021, utilizando o RFE RECURSIVE FEATURE ELIMINATIONS para verificar quais indicadores melhor funcionam dentro do setup.

A idéia deste projeto surgiu, de um curso de Estatística para Ciência de Dados e Machine Learning que estou fazendo pela UDEMY, e no curso tem um módulo onde explicam sobre algortimos, achei o funcionamento dos algoritimo e apliquei no estudo do gráfico ao qual opero no mercado finaceiro para tentar extrair insigths sobre como o preço de máxima e mínima dos preços, se comportam diante esses indicadores, os quais eu coloquei em um algoritmo de apredizado de máquina RFE e este me retornou quais os melhores a serem usados. Diante disto pltei alguns graficos para fazer a analise do comportamento do preço.

O setup usado na operação possui os seguitens indicadores:
- vwap diaria
- vwap semanal
- vwap mensal
- pontos pivot
- media movel 20 periodos
- media movel 200 periodos
- media movel 9 periodos

Usamos esses indicadores como variáveis característcas e comparamos com o preço de fechamento dos candles de 5min, passamos para um modelo de regressão linear usamos RFE para testar e tentar nos retornar quais são os melhores indicadores diante do que o RFE recomendar.
