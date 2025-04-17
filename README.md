# Projeto Modelo de Machine Learning - Previsão de Cancelamento de Operadora TV a Cabo <br>
📌 Visão Geral<br><br>
Neste projeto, desenvolvi um modelo preditivo de Machine Learning para prever o cancelamento de assinaturas (churn) de uma operadora de TV a Cabo. O objetivo principal é identificar clientes com alta probabilidade de cancelamento para que a empresa possa tomar ações preventivas e reduzir a taxa de evasão.<br><br>

🎯 Objetivos:<br>
- Realizar uma análise exploratória detalhada dos dados

 - Tratar valores missing e outliers

- Aplicar técnicas de engenharia de características (feature engineering)

- Desenvolver e avaliar modelos de classificação

- Criar um modelo preditivo com boa acurácia para identificar clientes propensos a cancelar<br><br>

📊 Dados:<br>
- Utilizei um conjunto de dados com mais de 440.000 registros contendo informações sobre:

- Dados demográficos dos clientes

- Serviços contratados

- Histórico de pagamentos

- Tempo de assinatura

- Padrões de uso

- Entre outras características relevantes<br><br>

🛠️ Tecnologias Utilizadas:<br>
- Python como linguagem principal

- Pandas e NumPy para manipulação de dados

- Matplotlib e Seaborn para visualização

- Scikit-learn para:

- train_test_split (divisão dos dados)

- StandardScaler (padronização)

- LabelEncoder (codificação)

- KNeighborsClassifier (algoritmo KNN)

- Métricas de avaliação (accuracy_score, etc.)

- SMOTE para balanceamento de classes

- Warnings para gerenciamento de alertas<br><br>

📈 Métodologia:<br>
- 1. Pré-processamento dos Dados
--Tratamento de valores missing

--Identificação e tratamento de outliers

--Análise das distribuições das variáveis

--Codificação de variáveis categóricas (One-Hot Encoding)<br>

- 2. Análise Exploratória (EDA)
--Análise univariada e multivariada

--Visualização das relações entre variáveis

--Identificação de padrões e correlações<br>

- 3. Engenharia de Atributos
--Criação de novas features relevantes

--Seleção das melhores características

--Normalização/padronização dos dados

- 4. Modelagem Preditiva
--Divisão em conjuntos de treino e teste

--Balanceamento da variável alvo com SMOTE

--Treinamento do modelo KNN

--Avaliação com métricas apropriadas

--Otimização de hiperparâmetros<br>

- 5. Avaliação do Modelo
--Análise da matriz de confusão

--Cálculo de acurácia, precisão, recall e F1-score

--Validação cruzada
