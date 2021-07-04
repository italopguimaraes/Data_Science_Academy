# Modelagem Preditiva em IoT:Previsão de Uso de Energia

*Previsão de consumo de energia de equipamentos eletrônicos*

Este projeto de IoT tem como objetivo a criação de modelos preditivos para
a previsão de consumo de energia de eletrodomésticos. Os dados utilizados
incluem medições de sensores de temperatura e umidade de uma rede sem fio,
previsão do tempo de uma estação de um aeroporto e uso de energia utilizada por
luminárias.
Utilizando para este projeto de aprendizado de máquina a filtragem de
dados para remover parâmetros não-preditivos e selecionar os melhores recursos
(melhores features) para previsão. O conjunto de dados foi coletado por um
período de 10 minutos por cerca de 5 meses. As condições de temperatura e
umidade da casa foram monitoradas com uma rede de sensores sem fio ZigBee.
Cada nó sem fio transmitia as condições de temperatura e umidade em torno
de 3 min. Em seguida, a média dos dados foi calculada para períodos de 10 minutos.
Os dados de energia foram registrados a cada 10 minutos com medidores de
energia de barramento m. O tempo da estação meteorológica mais próxima do
aeroporto (Aeroporto de Chievres, Bélgica) foi baixado de um conjunto de dados
públicos do Reliable Prognosis (rp5.ru) e mesclado com os conjuntos de dados
experimentais usando a coluna de data e hora. Duas variáveis aleatórias foram
incluídas no conjunto de dados para testar os modelos de regressão e filtrar os
atributos não preditivos (parâmetros).
O objetivo é construir um modelo preditivo que possa prever o
consumo de energia com base nos dados de sensores IoT coletados.

Esse projeto é parte da Formação Cientista de Dados da Data Science Academy

## Dependências de Software

Tenha certeza que `jupyter-notebook`,`pandas`,`numpy`,`seaborn`,`matplotlib`,`sklearn`,`tensorflow`,`xgboost`,`keras`,`graphviz` e `scipy` estão instalados:

`conda install pandas numpy seaborn matplotlib sklearn tensorflow xgboost keras graphviz scipy`

## Instruções do Projeto

1. Clone o repositório ou faça o download e navegue no diretório contendo o arquivo Modelagem_Preditiva_em_IoT_Previsão_de_Uso_de_Energia.rar e descompacte-o no mesmo diretótio, usando anaconda ou prompt de comando.

2. Agora basta executar o notebook Modelagem_Preditiva_em_IoT_Previsão_de_Uso_de_Energia.ipynb no jupyter notebook.
