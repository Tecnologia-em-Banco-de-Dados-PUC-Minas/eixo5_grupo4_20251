# Pré-Processamento dos Dados
A base de dados utilizada neste trabalho foi obtida na plataforma Kaggle e previamente preparada pelos criadores, que realizaram um processo robusto de tratamento e pré-processamento. Essa etapa inicial incluiu a limpeza dos dados, remoção de valores ausentes e a aplicação de normalizações, assegurando que o conjunto estivesse pronto para análises e desenvolvimento de modelos.

Foram realizadas ações adicionais para garantir a qualidade e funcionalidade dos dados:

## Importação de Ferramentas
Bibliotecas como Pandas e NumPy foram usadas para manipulação de dados, enquanto ferramentas de visualização como Matplotlib e Seaborn facilitaram a análise gráfica.

## Inspeção e Limpeza dos Dados
Confirmou-se que não havia valores ausentes ou duplicados, simplificando o pré-processamento.

## Codificação de Variáveis Categóricas
Variáveis categóricas foram transformadas em valores numéricos por meio de One-Hot Encoding e Binary Encoding, reduzindo dimensionalidade e facilitando sua aplicação em mode.

## Normalização de Recursos
Variáveis como MonthlyRate, MonthlyIncome e HourlyRate   foram reescaladas para o intervalo [0, 1] usando o MinMaxScaler, garantindo consistência nas análises.

Graças a essa preparação, foi possível direcionar o foco do trabalho diretamente à exploração e aplicação dos dados.
