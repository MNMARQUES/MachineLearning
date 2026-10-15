# Projeto de Machine Learning: Previsão de Preços de Imóveis com Regressão

## Objetivo do projeto

Este projeto foi desenvolvido como parte do desafio prático do Módulo 4 — Metodologias de Aprendizado, da formação de Engenheiro(a) de Machine Learning. O objetivo principal é aplicar conceitos de aprendizado de máquina supervisionado para desenvolver modelos capazes de prever preços de imóveis a partir de suas características físicas e geográficas.

Utilizando o conjunto de dados *House Sales Prediction*, disponibilizado no Kaggle, o projeto explora informações como quantidade de quartos e banheiros, área construída, tamanho do terreno, localização, conservação e padrão de construção dos imóveis, buscando identificar quais atributos contribuem para a estimativa de seus preços.

## Ferramentas e tecnologias utilizadas

- **Python:** linguagem de programação utilizada no desenvolvimento do projeto.
- **Google Colab:** ambiente de execução dos experimentos e desenvolvimento do código.
- **Pandas e NumPy:** manipulação, organização e análise dos dados.
- **Matplotlib e Seaborn:** visualização gráfica e análise exploratória dos dados.
- **Scikit-learn:** preparação dos dados, construção de pipelines, treinamento dos modelos e avaliação dos resultados.
- **Kaggle:** fonte do conjunto de dados utilizado no estudo.

## Metodologia aplicada

O desenvolvimento envolveu o carregamento e a inspeção dos dados, a análise exploratória, a seleção de atributos relevantes, a preparação das variáveis e a divisão da base em conjuntos de treinamento e teste.

Foram implementados e comparados dois algoritmos de regressão: **Regressão Linear** e **Random Forest Regressor**. A regressão linear foi utilizada como modelo de referência, enquanto a Random Forest permitiu investigar a capacidade de um algoritmo baseado em múltiplas árvores de decisão de capturar relações mais complexas entre as características dos imóveis e seus preços.

A avaliação dos modelos foi realizada por meio de métricas como **R² (coeficiente de determinação), MAE (erro absoluto médio) e RMSE (raiz do erro quadrático médio)**, permitindo analisar a capacidade explicativa e a magnitude dos erros das previsões.

## Resultados e aprendizado

A execução do projeto permitiu aplicar, na prática, etapas fundamentais de um fluxo de Machine Learning, desde a preparação dos dados até a comparação de modelos preditivos. A abordagem também possibilitou compreender a importância da escolha dos atributos, da separação entre treinamento e teste e da utilização de métricas adequadas para avaliar a qualidade das previsões.

A comparação entre os algoritmos fornece uma base objetiva para identificar qual modelo apresenta o melhor desempenho no conjunto de teste, considerando tanto a capacidade de explicar a variação dos preços quanto os erros cometidos nas estimativas.

## Conclusão

O projeto consolidou conhecimentos fundamentais de Engenharia de Machine Learning, demonstrando como técnicas de regressão podem ser aplicadas a um problema real de análise imobiliária. Além do desenvolvimento técnico em Python e Scikit-learn, a atividade reforçou a importância de uma metodologia estruturada, da avaliação criteriosa dos modelos e da interpretação dos resultados para a construção de soluções preditivas confiáveis.

Como evolução, o projeto pode incorporar técnicas de validação cruzada, otimização de hiperparâmetros, engenharia de atributos e análise da importância das variáveis, visando aprimorar o desempenho e a capacidade de generalização dos modelos.
