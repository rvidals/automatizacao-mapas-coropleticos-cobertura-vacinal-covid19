# Automatização de mapas coropléticos de cobertura vacinal de COVID-19

Esse projeto traz uma solução simples para a criação automatizada de mapas coropléticos da cobertura vacinal de COVID-19, cuja estratificação das classes são previamente definidas pelo usuário e usadas pelo Programa Nacional de Imunização (PNI) da Secretaria de Vigilância em Saúde (SVS) do Ministério da Saúde. 

O desenvolvimento desse script se dá no intuito de acelerar a entrega de mapas simples, usados em apresentações internas semanais. Dessa forma, devido a grande quantidade de demandas que tenho que entregar diaramente, houve a necessidade de automatizar a criação desse mapa. 

O projeto consiste nos seguintes passo:

1) Ler uma excel de cobertura vacinal por Unidade da Federação (UF) e faixa etária
2) Fazer o merge entre o shp de Unidade da Federação e o excel com cobertura vacinal por UF 
3) Gerar um mapa coroplético de cobertura vacinal por faixa etária com os seguintes elementos cartográficos:
    - Legenda;
    - Norte;
    - Escala e 
    - Sigla de cada UF

As bibliotecas usadas no desenvolvimento desse script são amplamente utilizadas na análise e ciência de dados e aplicações na área de geoprocessamento, utilizando python: 

  - seaborn
  - pandas
  - numpy
  - geopandas
  - pysal
  - mapclassify
  - matplotlib
  

