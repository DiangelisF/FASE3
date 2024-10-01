# Grupo_37 -  MACHINE LEARNING ENGINEERING

Tech Challenge FIAP - Fase 3

# Integrantes: 
- Débora Correia Campos
- Diangelis Barbato França
- Fabrício Zambom Galvani
- Vinicius Meira Albuquerque

# Introdução:
Criamos esse algoritmo Machine Learning para analisar a base histórica das ações da Petróleo Brasileiro S.A. - Petrobras (PETR4.SA) e tentar prever o seu valor de fechamento futuro. O projeto faz parte da terceira fase do Tech Challenge FIAP.
# Um problema de série temporal 
Uma série temporal em machine learning (ML) refere-se a uma sequência de pontos de dados coletados ou registrados ao longo do tempo em intervalos sucessivos. O principal desafio na modelagem de séries temporais é capturar padrões e dependências temporais para prever valores futuros com base nos dados históricos.

# O SageMaker e a previsão com DeepAR
O algoritmo de previsão Amazon SageMaker DeepAR é um algoritmo de aprendizado supervisionado para prever séries temporais escalares (unidimensionais) usando redes neurais recorrentes. Ele possui funções automáticas que foram usadas no projeto para agilizar a resolução do problema.

# dataset
Neste dataset apresentaremos um conjunto de dados extraídos de cotações de ações da Petrobras (PETR4.SA) disponível em: https://www.kaggle.com/datasets/delusdias/banco-do-brazil-sa-bbas3sa

Conteúdo:
- Date: data da cotação;
- Open: valor de abertura;
- High: maior valor;
- Low: menor valor;
- Close: valor de fechamento;
- Adj Close: valor de fechamento ajustado;
- Volume: quantidade de ações ou contratos que foram negociados;

# Dados de treinamento e dados de teste
A base de dados (BD) foi dividida em duas, a base treinamento é (BD-30medidas) e a base de teste são as 30 medidas restantes, portanto, não incluidas no treinamento. 
Em resumo:

# ENDPOINTS 
Exemplo: /producao
