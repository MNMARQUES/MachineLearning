# Relatório — Desafio de Modelos Preditivos e Séries Temporais

## Objetivo

O objetivo deste desafio foi desenvolver e avaliar modelos de Machine Learning para classificar cédulas bancárias como genuínas ou falsificadas, utilizando o dataset Banknote Authentication, disponibilizado pelo UCI Machine Learning Repository.

## Metodologia

Inicialmente, foi realizada uma análise exploratória dos dados utilizando Pandas, Matplotlib e Seaborn, incluindo inspeção das dimensões, tipos de dados, estatísticas descritivas, valores ausentes, distribuição das classes e correlações entre as variáveis.

As variáveis variance, skewness, curtosis e entropy foram utilizadas como atributos de entrada, enquanto a variável class foi definida como variável-alvo.

O dataset foi dividido em 70% para treinamento e 30% para teste, utilizando random_state=1. Foram implementados cinco algoritmos: K-Nearest Neighbors (KNN), Árvore de Decisão, Random Forest, Support Vector Machine (SVM) e Multilayer Perceptron (MLP), conforme os parâmetros especificados no desafio.


## Resultados e Conclusão

Após o treinamento e a avaliação dos cinco algoritmos de classificação, observou-se um desempenho elevado na identificação de cédulas genuínas e falsificadas.

Os modelos MLP (Multilayer Perceptron) e SVM (Support Vector Machine) obtiveram os melhores resultados, alcançando acurácia, precisão, recall e F1-score de 1,0000, equivalentes a 100% nas métricas apresentadas para o conjunto de teste.

O algoritmo KNN também apresentou excelente desempenho, com acurácia de 99,76% e F1-score de 0,9972. O Random Forest obteve acurácia de 99,51%, enquanto a Árvore de Decisão apresentou 98,79%.

Os resultados demonstram que os cinco algoritmos foram capazes de aprender padrões relevantes nos atributos numéricos do dataset Banknote Authentication. A comparação também evidenciou diferenças de desempenho entre os métodos, destacando o MLP e o SVM nesta divisão experimental.

Conclui-se que os objetivos propostos foram alcançados, contemplando a análise exploratória dos dados, a separação entre treinamento e teste, a implementação de diferentes algoritmos supervisionados e a comparação dos modelos por meio de métricas de classificação.

Como possibilidade de evolução, recomenda-se realizar validação cruzada e avaliar o desempenho em dados independentes adicionais, a fim de investigar a capacidade de generalização dos modelos antes de qualquer aplicação prática.

