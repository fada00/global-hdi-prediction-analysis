# 🌍 Global Human Development Analysis & Prediction (1990-2022)

## 📂 Dataset & Acknowledgements
This project utilizes the **Human Development Report (HDR) 2021-22** dataset, obtained via Kaggle and originally sourced from the United Nations Development Programme (UNDP).

* **Dataset Name:** [Human Development Index (HDI) Dataset 1990-2022]
* **Kaggle Source:** [Human Development Index Dataset on Kaggle](https://www.kaggle.com/datasets/lucasyukioimafuko/human-development-index-hdr-dataset-1990-2022)
* **Coverage:** The dataset spans from 1990 to 2022, including key indicators such as:
    * `hdi`: Human Development Index
    * `le`: Life Expectancy at birth
    * `gnipc`: Gross National Income Per Capita
    * `gii`: Gender Inequality Index
    * `co2_prod`: CO2 emissions per capita

> **Note:** The data is used for educational purposes to demonstrate regression and classification techniques in Python.

### 🚀 Project Goal
An analytical investigation of global human development trends using the HDR dataset (1990-2022). The project aims to predict the Human Development Index (HDI) using socioeconomic indicators and explore the impact of gender inequality and CO2 emissions.

### 🧠 Machine Learning Models
To predict HDI, the following models were implemented and compared:
* **Random Forest**
* **Support Vector Machines (SVM)**
* **Artificial Neural Networks (ANN)**
* **XGBoost**

### 📊 Key Insights
* **Gender Inequality:** Analysis of disparities in education and income across development groups.
* **Environmental Impact:** Correlation between CO2 emissions and high development levels.
* **Model Performance:**  Support Vector Machine (SVR) performed best with R^2 = 0.8934.

### 💻 Tech Stack
* **Python:** Pandas, Scikit-learn, Seaborn, Matplotlib.
* **Techniques:** Data Imputation, Regression Analysis, Clustering.

[📄 Read the Full Paper](Main/Docs/global-hdi-prediction-analysis.pdf) | [💻 View Notebook](Main/Notebooks/Global-hdi-prediction.ipynb)

