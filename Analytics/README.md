
---

# 📱 Análise de Aplicativos da Google Play Store

Este projeto tem como objetivo realizar uma análise exploratória de dados (EDA) utilizando a biblioteca **Pandas** para manipulação dos dados e **Matplotlib** para a visualização. Os dados analisados são provenientes de um dataset com informações sobre aplicativos da **Google Play Store**.

## 📊 Descrição do Projeto

No notebook `Analytics_Play_Store.ipynb`, realizamos uma análise detalhada dos dados de aplicativos disponíveis na Play Store, identificando tendências, padrões e insights úteis para entender o comportamento dos apps em relação a:

* Categorias mais populares
* Número de instalações
* Avaliações
* Tamanhos dos apps
* Preços e modelos de monetização
* Relação entre avaliações e classificações (ratings)

---

## 🧰 Tecnologias e Bibliotecas Usadas

* `pandas` – manipulação e limpeza de dados
* `matplotlib.pyplot` – geração de gráficos
* `numpy` – suporte numérico
* `seaborn` (em algumas seções) – visualizações estatísticas (opcional)

---

## 📂 Estrutura da Análise

1. **Importação e Leitura dos Dados**

   * Leitura do arquivo CSV com `pandas.read_csv()`
   * Exibição das 5 primeiras linhas para inspeção inicial

2. **Limpeza de Dados**

   * Remoção de valores duplicados
   * Conversão de colunas numéricas (como `Installs`, `Size`, `Price`)
   * Tratamento de valores ausentes (`NaN`)

3. **Análise Exploratória (EDA)**

   * Distribuição de categorias
   * Aplicativos gratuitos vs. pagos
   * Relação entre `Reviews`, `Installs` e `Rating`
   * Tamanho médio dos apps por categoria
   * Visualização de outliers e correlações

4. **Visualizações**

   * Gráficos de barras, histogramas e scatter plots com `matplotlib`
   * Tabelas agrupadas e classificadas com `groupby()`

---

## ▶️ Como Executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```

2. Acesse o diretório:

   ```bash
   cd seu-repositorio
   ```

3. Instale as dependências:

   ```bash
   pip install pandas matplotlib numpy
   ```

4. Execute o Jupyter Notebook:

   ```bash
   jupyter notebook Analytics_Play_Store.ipynb
   ```

---

## 📌 Conclusões

* A maioria dos aplicativos da Play Store são gratuitos.
* Apps com maior número de instalações tendem a ter melhores avaliações.
* Certas categorias dominam a loja, como jogos e ferramentas.
* O tamanho do app pode influenciar a avaliação do usuário em alguns casos.

---

## 📁 Fonte dos Dados

O dataset utilizado está disponível publicamente e pode ser encontrado no Kaggle:
[Google Play Store Apps Dataset](https://www.kaggle.com/lava18/google-play-store-apps)

---

## ✍️ Autor

Projeto adaptado e analisado por **\[Amadeus]**
Inspirado em análises públicas de dados da Play Store.




---

# 📱 Google Play Store Apps Analysis

This project aims to perform an **exploratory data analysis (EDA)** using the **Pandas** library for data manipulation and **Matplotlib** for visualization. The dataset contains information about apps available on the **Google Play Store**.

## 📊 Project Description

In the notebook `Analytics_Play_Store.ipynb`, we conduct a detailed analysis of app data from the Play Store, identifying trends, patterns, and valuable insights to understand app behavior regarding:

* Most popular categories
* Number of installs
* Ratings and reviews
* App sizes
* Pricing and monetization models
* Relationship between reviews and ratings

---

## 🧰 Technologies and Libraries Used

* `pandas` – data manipulation and cleaning
* `matplotlib.pyplot` – plotting and visualization
* `numpy` – numerical support
* `seaborn` (optional) – statistical data visualization

---

## 📂 Analysis Structure

1. **Data Import and Preview**

   * Reading the CSV file using `pandas.read_csv()`
   * Displaying the first 5 rows for initial inspection

2. **Data Cleaning**

   * Removing duplicate entries
   * Converting numeric columns (`Installs`, `Size`, `Price`)
   * Handling missing values (`NaN`)

3. **Exploratory Data Analysis (EDA)**

   * Distribution of app categories
   * Free vs. paid apps
   * Relationship between `Reviews`, `Installs`, and `Rating`
   * Average app size per category
   * Detecting outliers and correlations

4. **Visualizations**

   * Bar charts, histograms, and scatter plots using `matplotlib`
   * Grouped and sorted tables using `groupby()`

---

## ▶️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. Navigate to the project folder:

   ```bash
   cd your-repository
   ```

3. Install the required dependencies:

   ```bash
   pip install pandas matplotlib numpy
   ```

4. Launch the Jupyter Notebook:

   ```bash
   jupyter notebook Analytics_Play_Store.ipynb
   ```

---

## 📌 Conclusions

* Most apps on the Play Store are free.
* Apps with higher install counts tend to receive better ratings.
* Certain categories, such as games and tools, dominate the store.
* App size may influence user ratings in some cases.

---

## 📁 Dataset Source

The dataset used in this project is publicly available on Kaggle:
[Google Play Store Apps Dataset](https://www.kaggle.com/lava18/google-play-store-apps)

---

## ✍️ Author

Project adapted and analyzed by **\[Amadeus]**
Inspired by public Play Store data analysis examples.

---


