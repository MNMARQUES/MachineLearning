🚀 **Desafio concluído: Seleção de Modelos de Machine Learning**

Mais uma etapa concluída na minha jornada de aprofundamento em **Engenharia de Machine Learning**, aplicando na prática conceitos fundamentais para desenvolver, avaliar e selecionar modelos preditivos.

🎯 **Objetivo do projeto**

O objetivo foi implementar e comparar dois algoritmos de classificação, **Support Vector Classifier (SVC)** e **Random Forest Classifier**, utilizando técnicas de validação cruzada e otimização de hiperparâmetros para identificar qual modelo apresentou o melhor desempenho na métrica F1-score.

🛠️ **Ferramentas e tecnologias utilizadas**

- **Python:** linguagem principal para desenvolvimento da solução.
- **Pandas e NumPy:** manipulação e análise dos dados.
- **Scikit-learn:** construção dos modelos, pré-processamento, validação cruzada e avaliação de desempenho.
- **SciPy:** definição das distribuições utilizadas na busca aleatória de hiperparâmetros.
- **RandomizedSearchCV:** exploração de diferentes configurações dos modelos.
- **StratifiedKFold:** validação cruzada estratificada com 10 divisões, preservando a proporção das classes.
- **F1-score:** métrica utilizada para comparar o equilíbrio entre precisão e recall.

📊 **Resultados obtidos**

Foram realizadas cinco iterações de busca de hiperparâmetros para cada algoritmo, com `random_state = 5762` para garantir a reprodutibilidade das configurações aleatórias.

Os resultados médios de F1-score na validação cruzada foram:

• **SVC:** 0,203083  
• **Random Forest:** 0,395752

O Random Forest apresentou o melhor resultado entre as configurações avaliadas, com um F1-score aproximadamente 94,9% superior ao do SVC.

💡 **Principais aprendizados**

O desafio reforçou que a seleção de modelos vai além de escolher um algoritmo: envolve compreender os dados, preparar as variáveis, definir uma estratégia de validação adequada, otimizar hiperparâmetros e interpretar as métricas de desempenho.

Também ficou evidente que a escolha do modelo deve ser orientada por resultados experimentais, considerando as características do problema e os objetivos da classificação.

**Próximo passo:** aprofundar a exploração dos hiperparâmetros e investigar estratégias para melhorar o desempenho dos modelos.

#MachineLearning #EngenhariaDeMachineLearning #Python #ScikitLearn #DataScience #InteligenciaArtificial #MLOps
