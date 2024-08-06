## 📊 Análise dos Resultados do Modelo

Após o treinamento do modelo de previsão de estoque utilizando o AWS SageMaker Canvas, foram obtidas as seguintes métricas de desempenho:

- **Avg. wQL (Average Weighted Quantile Loss):** `0.060`
- **MAPE (Mean Absolute Percentage Error):** `0.148`
- **WAPE (Weighted Absolute Percentage Error):** `0.100`
- **RMSE (Root Mean Squared Error):** `5.765`
- **MASE (Mean Absolute Scaled Error):** `0.301`

### Interpretação das Métricas

1. **Avg. wQL (0.060):**
   - Esta métrica indica que o modelo está relativamente próximo dos valores reais, considerando a distribuição dos dados. Um valor de 0.060 sugere que as previsões do modelo têm uma precisão aceitável, especialmente em cenários onde a previsão por intervalos é relevante.

2. **MAPE (0.148):**
   - Com um MAPE de 0.148, o modelo apresenta um erro percentual médio de 14,8%. Isso significa que, em média, as previsões do modelo diferem em cerca de 14,8% dos valores reais. Para muitas aplicações de previsão de estoque, esse valor pode ser considerado bom, dependendo da volatilidade do mercado e da natureza dos dados.

3. **WAPE (0.100):**
   - O WAPE de 0.100 sugere que, ponderando as previsões de acordo com a importância dos diferentes itens no estoque, o modelo tem um erro médio de 10%. Isso é um sinal de que o modelo está fazendo um bom trabalho em geral, especialmente ao prever itens de maior valor ou volume.

4. **RMSE (5.765):**
   - O RMSE de 5.765 indica a magnitude do erro nas previsões, com maior peso dado a grandes desvios. Embora o valor absoluto do RMSE dependa da escala dos dados, ele sugere que há variações nos erros, com alguns valores previstos estando significativamente fora dos valores reais. Este é um ponto a ser observado, especialmente se houver dados outliers que possam estar afetando a performance do modelo.

5. **MASE (0.301):**
   - O MASE de 0.301 mostra que o modelo comete cerca de 30,1% do erro que um modelo de referência simples (como um modelo de persistência) cometeria. Isso sugere que o modelo atual é uma melhoria significativa em relação a previsões mais básicas, o que reforça a utilidade do modelo para previsões de estoque.

### Considerações Finais

No geral, as métricas indicam que o modelo tem um desempenho robusto para a tarefa de previsão de estoque, com um equilíbrio aceitável entre precisão e erro. No entanto, o RMSE sugere que há variação nos erros, o que pode merecer uma investigação mais detalhada, especialmente se houver outliers ou se o desempenho do modelo precisar ser ajustado para casos específicos. Se necessário, ajustes adicionais no modelo ou nos dados de entrada podem ser feitos para melhorar ainda mais a precisão das previsões.
