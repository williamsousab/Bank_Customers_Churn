<div align="center">
<img src="https://github.com/williamsousab/Bank_Customers_Churn/blob/main/images/dataset-cover.jpg?raw=true?t=2019-08-03-18-19-59?raw=true" width="700px" />
</div> 

# 🏦 Bank Customers Churn

Projeto de análise e predição da rotatividade de clientes de banco usando técnicas de machine learning e análise exploratória de dados. O objetivo é entender quais fatores influenciam a saída de clientes e construir um modelo preditivo eficaz.

---

## 📁 Dataset

- Fonte: [Kaggle – Bank Customers Dataset](https://www.kaggle.com/datasets/santoshd3/bank-customers)
- Atributos principais:
  - `CreditScore`, `Geography`, `Gender`, `Age`, `Tenure`
  - `Balance`, `NumOfProducts`, `HasCrCard`, `IsActiveMember`
  - `EstimatedSalary`, `Exited` (variável alvo)

---

## 🔍 Análise Exploratória de Dados (EDA)

- Inspeção de valores ausentes e duplicados
- Visualização da distribuição das variáveis com histogramas e boxplots
- Análise da relação entre idade e saída dos clientes:
  - Scatterplot, histogramas e boxplot por `Exited`
- Matriz de correlação entre variáveis numéricas
- Avaliação de importância das variáveis com `RandomForestClassifier`

---

## 🧠 Modelagem de Machine Learning

### 🔹 Algoritmo Utilizado
- `Random Forest Classifier` com e sem ajuste de hiperparâmetros

### 🎯 Métricas de Avaliação
- Acurácia: **86.6%**
- Precisão: **75.2%**
- Recall: **46.7%**
- F1-Score: **57.7%**

### 🔧 Ajuste de Hiperparâmetros (Grid Search)
- `n_estimators`: 100
- `max_depth`: 20
- `min_samples_split`: 10
- `min_samples_leaf`: 4
- `max_features`: `'sqrt'`

---

## 📊 Visualizações

- Matriz de confusão (pré e pós otimização)
- Gráficos de métricas (Acurácia, Precisão, Recall, F1-Score)
- Importância das variáveis preditoras

---

## 🛠️ Tecnologias e Bibliotecas

- Python 3.11+
- `pandas`, `numpy`
- `seaborn`, `matplotlib`
- `scikit-learn`
- `joblib` (salvar modelo)

---
