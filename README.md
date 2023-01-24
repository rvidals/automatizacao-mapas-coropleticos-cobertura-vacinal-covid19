# Automatização de mapas coropléticos de cobertura vacinal de COVID-19

Esse projeto traz uma solução simples para a criação automatizada de mapas coropléticos da cobertura vacinal de COVID-19, cuja estratificação das classes são previamente definidas pelo usuário e usadas pelo Programa Nacional de Imunização (PNI) da Secretaria de Vigilância em Saúde (SVS) do Ministério da Saúde. 

O desenvolvimento desse script se dá no intuito de acelerar a entrega de mapas simples, usados em apresentações internas semanais. Dessa forma, devido a grande quantidade de demandas que tenho que entregar diaramente, busquei uma solução simples que otimizava tempo e processamento para a criação desses mapas. 

O projeto consiste nos seguintes passos:

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
  
Segue o exemplo de alguns mapas gerados a partir do script:

<div align="center">
<img src="https://user-images.githubusercontent.com/115746365/214355405-b9c99243-5d82-412f-9fa2-53426e0d6489.png" width="700px" />
</div>

<div align="center">
<img src="https://user-images.githubusercontent.com/115746365/214355605-9126ac16-eb76-4384-971c-7213a5f6c00c.png" width="700px" />
</div>

<div align="center">
<img src="https://user-images.githubusercontent.com/115746365/214355649-7aa83e06-30be-49c7-bedd-e239a6ff57c9.png" width="700px" />
</div>




