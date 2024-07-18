# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

- Foi selecionado o DataSet de "produtos eletrônicos" para gerar o modelo de Marchine Learn. 

- Selecionando a coluna de "demand" para prêver os valores com 20.0k de linhas no DataSet.

- A análise do status do modelo foi gerado da seguinte forma:

Avg. wQL (Perda média de quantil ponderada)
0.013 
 
MAPE (Média Percentual Absoluta do Erro)
0.025

WAPE (Erro Percentual Absoluto Ponderado )
0.021

RMSE (Raiz Quadrada do Erro Médio)
2079.610

MASE (erro escalado absoluto médio)
0.000


Colunas que aumentam as pontuações de precisão no período de 1 mês:

price
45.99%

Location
54.01%


As previsões da coluna "Acessories" do período de 01/09/2019 a 01/10/2019, foram geradas em enviadas para a pasta "datasets" com o nome do arquivo: "sigle_prediction_results.csv




