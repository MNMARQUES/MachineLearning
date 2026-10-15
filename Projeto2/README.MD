# Relatório — Desafio de Modelos Preditivos e Séries Temporais

## Objetivo

O objetivo deste desafio foi desenvolver e avaliar modelos de Machine Learning para classificar cédulas bancárias como genuínas ou falsificadas, utilizando o dataset Banknote Authentication, disponibilizado pelo UCI Machine Learning Repository.

## Metodologia

Inicialmente, foi realizada uma análise exploratória dos dados utilizando Pandas, Matplotlib e Seaborn, incluindo inspeção das dimensões, tipos de dados, estatísticas descritivas, valores ausentes, distribuição das classes e correlações entre as variáveis.

As variáveis variance, skewness, curtosis e entropy foram utilizadas como atributos de entrada, enquanto a variável class foi definida como variável-alvo.

O dataset foi dividido em 70% para treinamento e 30% para teste, utilizando random_state=1. Foram implementados cinco algoritmos: K-Nearest Neighbors (KNN), Árvore de Decisão, Random Forest, Support Vector Machine (SVM) e Multilayer Perceptron (MLP), conforme os parâmetros especificados no desafio.

## Avaliação

Os modelos foram treinados e avaliados utilizando o conjunto de teste. Para a comparação, foram calculadas as métricas de acurácia, precisão, recall e F1-score, além das respectivas matrizes de confusão.

**Melhor resultado observado:** [preencher após a execução].

**Acurácia do melhor modelo:** [preencher com o valor obtido].

## Conclusão

O experimento permitiu aplicar conceitos de análise exploratória, preparação de dados, treinamento supervisionado e avaliação comparativa de classificadores.

A comparação entre os algoritmos possibilitou observar diferenças de desempenho na identificação das classes e compreender a importância de utilizar múltiplas métricas para avaliar modelos preditivos.

Os resultados obtidos demonstram como técnicas de Machine Learning podem ser aplicadas a problemas de classificação com dados numéricos extraídos de imagens, respeitando a necessidade de avaliar o desempenho em dados não utilizados durante o treinamento.
