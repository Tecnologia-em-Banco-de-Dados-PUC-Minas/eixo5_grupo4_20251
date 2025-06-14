# Análise dos resultados

Neste projeto de Machine Learning foram utilizados diversos modelos de classificação para prever a evasão de funcionários, são eles:

Regressão Logística: O modelo é assertivo na previsão dos que permanecem, mas possui um recall baixo para os que saem, pois existe um desbalanceamento nas classes. Isso faz com que a classe dos que vão sair não seja percebida corretamente.

Random Forest: O modelo possui uma boa acurácia para prever a classe dos funcionários que permanecem, mas o modelo apresentou um overfitting mesmo após o tuning de hiperparâmetros, projeta um recall ruim na classe minoritária.

Support Vector Machine: Utilizou-se duas formas para essa modelo a linear (sem otimização) e a otimizada com GridSearchCV, o modelo otimizado demonstrou melhor desempenho na acuaria, na precision e no recall, mas ambos possuem um desempenho ruim em detectar a classe minoritária.

Os modelos XGBoost, LightGBM, CastBoost. apresentam uma boa acurácia entre 85%, mas baixa captura da classe minoritária, todos apresentam overfitting em sua execução mesmo que o CastBoost possua um overfitting menor.

Entre todos os modelos, o XGBoost apresentou o melhor desempenho com uma pontuação roc_auc de 0.622, seguido pelo LightGBM (0.609) e pelo CatBoost (0.586). Modelos como Random Forest e Regressão Logística tiveram desempenho 
intermediário, enquanto o SVM obteve o menor resultado, com roc_auc de 0.500,equivalente a uma escolha aleatória.

Em análise o XGBoost foi o melhor modelo aplicado para prever a evasão dos funcionários, ele mostrou que a precision e o recall da classe dos funcionários que permanecem tem uma boa previsão, mas a classe dos funcionários que saem ainda possui baixa detecção, esses baixa detecção pode ser corrigida com algumas mudanças de parâmetros. Mas mesmo diante desse desbalanceamento de classes,
esse modelo ainda é eficiente para a responder as perguntas de negócio apresentas.
