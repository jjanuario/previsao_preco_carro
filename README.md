# Previsão de preços de carros usando machine learn.

![Funny Predction](funnyPrediction.jpeg)

## As estapas a serem seguidas neste caso de estudo são;

1. Criar um modelo

    - [x] Obter os dados
    Dados obtidos via Microsoft Azure Machine Learn Studio [dados](automobile_price_data_raw_.csv)
    - [x] Preparar os dados
    Aqui realizei a limpeza dos dados excluindo a coluna 'normalized-losses' e todas as linhas com dados faltantes.
    ```python
    # Removendo a coluna normalized-losses
    df = df.drop('normalized-losses', axis=1)
    # Apagando todas as linhas com dados faltantes
    df.dropna(inplace=True)
    ```
    - [ ] Definir recursos
    
2. Treinar o modelo

    - [ ] Escolher e aplicar um algoritmo

3. Pontuar e testar o modelo

    - [ ] Prever novos preços de automóveis
