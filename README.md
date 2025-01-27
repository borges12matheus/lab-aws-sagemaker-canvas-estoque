# Previsão de Estoque Inteligente 📦

Este projeto utiliza o [AWS SageMaker Canvas](https://aws.amazon.com/sagemaker/canvas/) para criar uma solução inteligente de previsão de estoque. O objetivo é ajudar empresas a otimizar seu inventário, evitando tanto a falta de produtos quanto o excesso de estoque.

## 🔍 Visão Geral

A previsão de estoque é essencial para uma gestão eficiente, minimizando custos e melhorando a satisfação dos clientes. Este projeto é dividido em quatro partes principais:

1. **Selecionar Dataset**: Escolha de um conjunto de dados adequado que contenha informações históricas de vendas, datas, produtos, entre outros fatores relevantes.
   
2. **Construir e Treinar**: Construção do modelo preditivo utilizando o SageMaker Canvas e técnicas de Machine Learning. O modelo é treinado para aprender padrões históricos e fornecer previsões precisas.

3. **Analisar**: Avaliação dos resultados do modelo, verificando métricas de performance e identificando possíveis melhorias.

4. **Prever**: Utilização do modelo para gerar previsões de estoque futuras, auxiliando na tomada de decisão estratégica.

## 🚀 Começando

### Pré-requisitos

- Uma conta na AWS
- Acesso ao [AWS SageMaker Canvas](https://aws.amazon.com/sagemaker/canvas/)
- Familiaridade com conceitos básicos de machine learning e análise de dados

### Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/borges12matheus/lab-aws-sagemaker-canvas-estoque
   ```
2. Acesse o SageMaker Canvas através do console AWS e siga as etapas descritas.

## 🗂 Estrutura do Projeto

- `dataset/`: Contém o conjunto de dados utilizado para o treinamento do modelo. O dataset utilizado para o treinamento do modelo foi o [dataset-1000-com-preco-promocional-e-renovacao-estoque.csv]
- `results/`: Resultados e previsões geradas pelo modelo.

## 💡 Como Funciona

1. **Selecionar Dataset**: No SageMaker Canvas, carregue seu dataset. Certifique-se de que os dados estão limpos e formatados corretamente.
   
2. **Construir e Treinar**: Configure os parâmetros de treinamento no SageMaker Canvas e inicie o treinamento do modelo.

3. **Analisar**: Após o treinamento, use as ferramentas de análise do SageMaker Canvas para revisar a performance do modelo.

4. **Prever**: Utilize o modelo treinado para gerar previsões e exporte os resultados para tomada de decisão.

## 📝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## 📄 Licença

Este projeto é licenciado sob a [MIT License](LICENSE).

---

Desenvolvido por [Matheus Borges](https://github.com/borges12matheus).
