# Clustering de Pinguins com K-Means

## 📚 Visão Geral

Este projeto aplica o algoritmo **K-means** para agrupar pinguins com base em características físicas, como o comprimento e a profundidade do bico, o comprimento das nadadeiras e a massa corporal. O objetivo é identificar padrões no conjunto de dados, sem informações sobre as espécies dos pinguins.

Embora o conjunto de dados não tenha rótulos de espécies, o algoritmo de K-means ajuda a criar clusters que podem ser analisados para inferir possíveis espécies, como Adelie, Chinstrap e Gentoo.

## ⚙️ Tecnologias Usadas

- **Python**
- **Pandas** para manipulação de dados
- **Matplotlib** para visualização de dados
- **Scikit-learn** para o algoritmo de K-means
- **StandardScaler** para pré-processamento dos dados

## 📝 Passos Realizados

1. **Exploração dos Dados**: Carreguei e examinei o conjunto de dados para entender as variáveis disponíveis.
2. **Pré-processamento dos Dados**: Converti variáveis categóricas em variáveis dummy e padronizei os dados para melhorar os resultados do clustering.
3. **K-Means Clustering**: Apliquei o algoritmo K-means para identificar o número ideal de clusters utilizando o método do cotovelo (elbow method).
4. **Análise**: Analisei os clusters e identifiquei as principais características físicas de cada grupo.
5. **Resultado Final**: Gere a tabela de características médias de cada cluster.

## 🔍 Conjunto de Dados

O conjunto de dados **penguins.csv** contém as seguintes colunas:

- **culmen_length_mm**: Comprimento do bico (em mm)
- **culmen_depth_mm**: Profundidade do bico (em mm)
- **flipper_length_mm**: Comprimento das nadadeiras (em mm)
- **body_mass_g**: Massa corporal (em gramas)
- **sex**: Sexo do pinguim

## 📈 Visualizações

O projeto inclui gráficos para ajudar a entender a distribuição dos clusters e suas características físicas.

---

<details id="versao-em-inglês">
<summary>English Version</summary>

## 📚 Overview

This project applies the **K-means** algorithm to cluster penguins based on physical characteristics, such as bill length, bill depth, flipper length, and body mass. The goal is to identify patterns in the dataset, without species information.

Although the dataset does not include species labels, the K-means algorithm helps to create clusters that can be analyzed to infer possible species, such as Adelie, Chinstrap, and Gentoo.

## ⚙️ Technologies Used

- **Python**
- **Pandas** for data manipulation
- **Matplotlib** for data visualization
- **Scikit-learn** for K-means algorithm
- **StandardScaler** for data preprocessing

## 📝 Steps Taken

1. **Data Exploration**: Loaded and examined the dataset to understand the available variables.
2. **Data Preprocessing**: Converted categorical variables to dummy variables and standardized the data to improve clustering results.
3. **K-Means Clustering**: Applied the K-means algorithm to identify the optimal number of clusters using the elbow method.
4. **Analysis**: Analyzed the clusters and identified the key physical characteristics of each group.
5. **Final Result**: Generated the mean characteristic table for each cluster.

## 🔍 Dataset

The dataset **penguins.csv** contains the following columns:

- **culmen_length_mm**: Bill length (in mm)
- **culmen_depth_mm**: Bill depth (in mm)
- **flipper_length_mm**: Flipper length (in mm)
- **body_mass_g**: Body mass (in grams)
- **sex**: Penguin sex

## 📈 Visualizations

The project includes graphs to help understand the distribution of clusters and their physical characteristics.



