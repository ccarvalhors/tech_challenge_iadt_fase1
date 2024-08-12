# **Modelo Preditivo para Precificação de Seguros de Saúde**

Este projeto, desenvolvido como parte da avaliação da primeira fase da pós-graduação em IA para Devs na FIAP, visa desenvolver um modelo preditivo para precificação de seguros de saúde utilizando técnicas de aprendizado de máquina. O objetivo deste desafio técnico é prever os custos médicos individuais com base em variáveis como idade, gênero, IMC, número de filhos, hábito de fumar, região de residência e encargos já cobrados.

## **Componentes do Grupo 10**

- Cristiano Carvalho
- Fabiano Pimenta
- Gabriel Neves
- Gustavo Pinheiro

## **Para utilizar este projeto:**

1. **Abra o notebook no [Google Colab](https://colab.google/).** (recomendado)
2. **Faça o upload do arquivo "seguro_saude.csv" para o ambiente do Colab.**

## **O notebook contém as seguintes etapas:**

- Importação das bibliotecas necessárias (pandas, numpy, matplotlib, seaborn, sklearn, etc.)
- Importação e exploração dos dados do arquivo "seguro_saude.csv".
- Análise descritiva dos dados, incluindo histogramas, gráficos de dispersão e tabelas de frequência.
- Pré-processamento dos dados categóricos (gênero, fumante, região) utilizando codificação ordinal e one-hot encoding.
- Análise de correlação entre as variáveis.
- Treinamento e avaliação de diferentes modelos de regressão:
  - Regressão Linear
  - Árvore de Decisão
  - Random Forest
- Comparação do desempenho dos modelos utilizando métricas como R², RMSE e MAE.
- Conclusões sobre o modelo mais adequado para a previsão dos custos médicos.

## **Observações:**

- O arquivo "seguro_saude.csv" deve estar no mesmo diretório do notebook ou ser carregado para o ambiente do Colab.
- Certifique-se de ter as bibliotecas necessárias instaladas no ambiente do Colab.

## **Para executar o notebook, siga as instruções no próprio arquivo.**

Este projeto oferece uma solução completa para a previsão de custos médicos individuais, auxiliando na otimização da precificação de seguros de saúde.
