# Life Expectancy Prediction Analysis
### TS Academy Capstone Project | Group 18

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Data-Science](https://img.shields.io/badge/Domain-Data%20Science-orange.svg)
![Machine-Learning](https://img.shields.io/badge/Focus-Machine%20Learning-green.svg)

## 📌 Project Overview
This project focuses on identifying and analysing the key factors that influence life expectancy globally. Utilising a comprehensive dataset, we perform rigorous **Exploratory Data Analysis (EDA)**, address potential **Data Leakage**, and build predictive models to understand how socio-economic factors, immunization, and mortality rates impact human longevity.

## 📊 Dataset Features
The analysis examines several critical indicators across various countries:
* **Immunisation:** Hepatitis B, Polio, and Diphtheria coverage.
* **Mortality:** Adult mortality, infant deaths, and under-five deaths.
* **Socio-Economic:** GDP, Schooling, and Income composition of resources.
* **Health Factors:** Alcohol consumption, BMI, and HIV/AIDS prevalence.

## 🛠️ Technical Workflow
The `Life_Expectancy_.ipynb` notebook follows a structured data science pipeline:

1. **Data Cleaning:** Handling missing values and ensuring consistency across country-year records.
2. **Feature Engineering:** Identifying and removing features that cause "Data Leakage" (such as the Human Development Index) to ensure model integrity.
3. **Exploratory Data Analysis (EDA):** Visualising correlations between life expectancy and factors like GDP, BMI, and Schooling.
4. **Predictive Modelling:** Implementing regression models to predict life expectancy based on health and economic metrics.
5. **Evaluation:** Assessing performance using metrics such as $R^2$ (R-Squared) and Mean Absolute Error (MAE).

## 🚀 Getting Started
To view or run the analysis locally:

1. **Clone the Repository:**
```bash
   git clone [https://github.com/Jammijuix/TS-Academy-Capstone-Projects-Group-18.git](https://github.com/Jammijuix/TS-Academy-Capstone-Projects-Group-18.git)
```

2 **Install Dependencies:**
Ensure you have the following libraries installed:

```Bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
Run the Notebook:
Open the `Life_Expectancy_.ipynb` file using Jupyter Notebook, JupyterLab, or VS Code.

📈 **Key Insights**
* Economic Correlation: There is a strong positive correlation between a country's GDP/Schooling and higher life expectancy.

* Healthcare Impact: Significant impact of immunisation coverage (Polio, Diphtheria) on reducing child mortality.

* Risk Factors: High HIV/AIDS prevalence remains a primary factor in lower life expectancy in specific regions.

👥 Group 18 Contributors
1. Nnamdi Kelvin Etumnu – Data Analysis & Modelling
2. Adeniji Mayowa 
3. Joseph Odili Alex 
4. Obichukwu Adaeze Suzan 
5. Akinseye Daniel Jesutimileyin 
6. Eniola Abimbola 
7. Solomon Ojukotimi 
8. Abraham Emenuvwe 
9. Inoghie David Ebunoluwa 
10. Caleb Kazayet Kadon 
11. Azeez Adekunle Ogunsina 
12. Issa Hamidat Olamide 
   ```bash
   git clone [https://github.com/Jammijuix/TS-Academy-Capstone-Projects-Group-18.git](https://github.com/Jammijuix/TS-Academy-Capstone-Projects-Group-18.git)
