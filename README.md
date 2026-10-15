# Fundamentos de Machine Learning: Classificação da Qualidade de Vinhos

## Objetivo do projeto

Este projeto teve como objetivo aplicar conceitos fundamentais de Aprendizado de Máquina (*Machine Learning*) para desenvolver e avaliar modelos de classificação capazes de prever a qualidade de vinhos tintos a partir de suas características físico-químicas.

A partir do conjunto de dados **Wine Quality**, foram realizadas etapas de análise exploratória dos dados (EDA), preparação e normalização das variáveis, divisão entre conjuntos de treinamento e teste e treinamento de diferentes algoritmos de classificação.

## Ferramentas e tecnologias utilizadas

- **Python:** linguagem de programação utilizada na implementação dos experimentos.
- **Google Colab:** ambiente de desenvolvimento em nuvem para execução do código Python.
- **Pandas e NumPy:** manipulação, organização e análise dos dados.
- **Matplotlib e Seaborn:** criação de gráficos para visualização e exploração dos dados.
- **Scikit-learn:** biblioteca utilizada para preparação dos dados, treinamento dos modelos e avaliação dos resultados.

## Metodologia aplicada

O desenvolvimento foi dividido em etapas:

1. **Análise exploratória (EDA):** investigação da estrutura do dataset, estatísticas descritivas, distribuição das classes e identificação de possíveis inconsistências.
2. **Preparação dos dados:** definição das características físico-químicas como variáveis de entrada e da coluna `quality` como variável de saída.
3. **Normalização:** aplicação do `MinMaxScaler` para ajustar as escalas das variáveis de entrada.
4. **Divisão dos dados:** separação em 70% para treinamento e 30% para teste, utilizando `random_state=1`.
5. **Treinamento dos modelos:** implementação e comparação de cinco algoritmos de classificação:
   - K-Nearest Neighbors (KNN);
   - Árvore de Decisão (*Decision Tree*);
   - Floresta Randômica (*Random Forest*);
   - Support Vector Machine (SVM);
   - Rede Neural Multilayer Perceptron (MLP).
6. **Avaliação dos resultados:** comparação do desempenho dos modelos por meio de métricas como acurácia, precisão, recall e F1-score, além da análise da matriz de confusão.

## Resultados e aprendizado

A execução do projeto permitiu compreender, na prática, como estruturar um fluxo de trabalho de Machine Learning, desde a exploração dos dados até a avaliação dos modelos treinados.

A comparação entre diferentes algoritmos possibilitou observar como cada abordagem pode apresentar desempenhos distintos diante de um mesmo problema de classificação. O projeto também reforçou a importância da normalização, da separação adequada dos dados e da utilização de métricas complementares para uma avaliação mais consistente.

## Conclusão

Este desafio representou uma aplicação prática dos fundamentos de Aprendizado de Máquina, consolidando conhecimentos em análise de dados, preparação de atributos, classificação supervisionada e avaliação de modelos.

Mais do que implementar algoritmos, o projeto demonstrou a importância de construir experimentos organizados e reproduzíveis, utilizando ferramentas do ecossistema Python para transformar dados em informações úteis para a tomada de decisão.

**Principais competências desenvolvidas:** Python, análise exploratória de dados, pré-processamento, Machine Learning, classificação supervisionada, Scikit-learn e avaliação de modelos.
