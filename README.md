# Desafio Bravium - Análise de Sentimento de Reviews

Este repositório contém a resolução do desafio de Machine Learning para o processo seletivo de Estágio em Inteligência Artificial da Bravium.

## Objetivo

O objetivo do projeto foi desenvolver um modelo de classificação para identificar se uma review de produto, extraída do dataset Olist, é **positiva** ou **negativa**.

## Metodologia

1.  **Análise Exploratória dos Dados:** Investigação inicial dos dados para entender as distribuições e correlações.
2.  **Engenharia de Features:** Criação da variável alvo (sentimento) a partir da coluna de notas (`review_score`).
3.  **Pré-processamento de Texto:** Limpeza e transformação dos comentários das reviews utilizando técnicas como TF-IDF.
4.  **Modelagem:** Treinamento e avaliação de um modelo de Regressão Logística.
5.  **Resultados:** O modelo final alcançou uma acurácia de 92% e um F1-score de 0.94 para a classe positiva.

## Como Executar

O notebook `analisar_sentimento.ipynb` contém todo o código e as análises. Para executá-lo, é necessário ter as bibliotecas listadas no arquivo `requirements.txt` (se você criar um) ou as principais bibliotecas de Data Science como Pandas, Scikit-learn, Seaborn, etc.
