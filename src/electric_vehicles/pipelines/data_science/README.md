# Pipeline data_science

## Visão geral

Modelagem para projeção de preço de revenda de carros puramente elétricos.

## Pipeline inputs

- bev_resale_database (Base de dados contendo transações de compra e venda de carros elétricos)

## Pipeline outputs

- resale_price_regressor (Modelo de regressão para previsão de preço de revenda de carros elétricos)
- prediction_plot (Gráfico para avaliação visual do modelo de regressão, com base em dados de teste)

## Performance do modelo

### Métricas

- R2: 0.9
- MAE: 3853
- MAPE: 19.26%

### Gráfico de previsão

![prediction_plot](/docs/images/prediction_plot.png)