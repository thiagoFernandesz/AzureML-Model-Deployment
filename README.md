# Projeto de Machine Learning no Azure ML

Este projeto tem como objetivo demonstrar a criação e implantação de um modelo de previsão utilizando o Azure Machine Learning.

## Passo a Passo

1. **Criação do Modelo:**
   - Utilizamos o Azure Machine Learning Studio para carregar os dados e criar um modelo de previsão de vendas.
   - Realizamos a preparação dos dados, incluindo limpeza, transformação e seleção de características.
   - Experimentamos vários algoritmos de aprendizado de máquina para encontrar o melhor desempenho.

2. **Configuração dos Pontos de Extremidade:**
   - Após selecionar o melhor modelo, configuramos os pontos de extremidade para permitir acesso ao modelo via API.
   - Definimos os métodos de comunicação (por exemplo, POST para envio de dados e GET para solicitação de previsões em tempo real).
   - Garantimos a segurança e a autenticação adequadas para proteger os pontos de extremidade.

3. **Implantação do Modelo:**
   - Utilizamos o Azure Machine Learning para implantar o modelo em produção.
   - Testamos a implantação para garantir que o modelo esteja funcionando conforme esperado.

## Como Utilizar

Para utilizar o modelo de previsão, siga estas etapas:

1. Envie uma solicitação para o ponto de extremidade de previsão com os dados relevantes.
2. Receba a resposta do modelo contendo a previsão desejada.
3. Analise os resultados e utilize as previsões para tomar decisões informadas.
