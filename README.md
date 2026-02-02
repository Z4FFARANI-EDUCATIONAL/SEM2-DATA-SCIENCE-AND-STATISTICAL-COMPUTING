# DATA SCIENCE & STATISTICAL COMPUTING

Este repositório contém notebooks desenvolvidos para a disciplina de Data Science % Statistical Computing, abrangendo análises exploratórias, estatísticas descritivas e modelos de machine learning (regressão e classificação).

Abaixo estão os detalhes de cada projeto:

## CHECKPOINT 4 (CP4)

Análise estatística focada em dois datasets distintos: o naufrágio do Titanic e listagens do Airbnb em Nova York.

- **Descrição:**
  - **Titanic:** Análise de taxas de sobrevivência baseadas em classe social, sexo, idade e família. Limpeza de dados (drop de colunas irrelevantes, tratamento de nulos) e agrupamentos estatísticos.
  - **Airbnb NYC:** Análise exploratória de anúncios, incluindo limpeza de dados, tradução de colunas, contagem de frequências por bairro e análise de reviews para determinar a distribuição de anúncios e tipos de acomodação preferidos.
- **Tecnologias:** Python, Pandas, NumPy, Matplotlib.
- **Arquivo Principal:** `CP4/CP4_DS_SC.ipynb`

## GLOBAL SOLUTION (GS)

**Projeto: O Futuro do Trabalho em Dados e Inteligência Artificial**

Uma análise aprofundada sobre o mercado de trabalho em Data Science, explorando salários, tipos de contrato e distribuição global.

- **Descrição:**
  - Análise Descritiva e Exploratória (EDA) sobre salários de cientistas de dados (média, mediana, desvio-padrão).
  - Estudo da correlação entre salários, tamanho da empresa e modelos de trabalho (remoto, híbrido, presencial).
  - Comparação salarial por nível de experiência e localização geográfica.
- **Tecnologias:** Python, Pandas, Matplotlib, Seaborn, Scikit-learn (LabelEncoder).
- **Arquivo Principal:** `GS/GS_DS_SC.ipynb`

## SPRINT 3

Foco em modelagem preditiva utilizando técnicas de regressão para estimar a demanda laboratorial.

- **Descrição:**
  - Implementação de Regressão Linear, Regressão Ridge (L2) e Regressão Lasso (L1).
  - Utilização de `GridSearchCV`/`RidgeCV`/`LassoCV` para otimização de hiperparâmetros (alfa).
  - Análise de coeficientes para seleção de features.
  - Exploração de Regressão Polinomial (2º e 3º grau) para capturar tendências não-lineares nos dados.
- **Tecnologias:** Python, Pandas, NumPy, Matplotlib, Scikit-learn (LinearRegression, Ridge, Lasso, PolynomialFeatures, StandardScaler).
- **Arquivo Principal:** `SPRINT3/SPRINT3_DS_SC.ipynb`

## SPRINT 4

Resolução de um problema de classificação para determinar a confiabilidade de fornecedores baseando-se em critérios de qualidade e logística.

- **Descrição:**
  - Criação de um dataset sintético de fornecedores com pontuações em certificados, rastreabilidade, suporte, logística e qualidade.
  - Implementação do algoritmo **KNN (K-Nearest Neighbors)** para classificação.
  - Otimização do valor de `k` via validação cruzada.
  - Implementação e comparação com **Regressão Logística**.
  - Avaliação de modelos utilizando Acurácia, Precisão, Recall, F1-Score e Matriz de Confusão.
- **Tecnologias:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn (KNeighborsClassifier, LogisticRegression, metrics).
- **Arquivo Principal:** `SPRINT4/SPRINT4_DS_SC.ipynb`

<br>

# TECNOLOGIAS

[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org/)
[![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://matplotlib.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)](https://scikit-learn.org/stable/)
