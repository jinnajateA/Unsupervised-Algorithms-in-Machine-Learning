# DTSA 5510 Unsupervised Algorithms in Machine Learning Final Project  
### Problem Definition

This project focuses on applying **unsupervised machine learning** techniques to cluster countries based on a set of **socio-economic and health indicators**.  
The aim is to identify groups of countries with similar development profiles in order to inform international aid allocation decisions.  
This is a **clustering problem**, where the model should uncover hidden patterns in the data without using any labels.

---

### Problem Description

**HELP International**, a global humanitarian NGO, has raised **$10 million** in funding.  
The CEO needs to determine **which countries should be prioritized** for receiving aid.  
As a data scientist, your task is to use clustering algorithms to analyze the countries’ development data and recommend the countries most in need of assistance.

By using unsupervised learning, we can form meaningful clusters of countries and guide HELP International in making **data-driven decisions** to strategically deploy their resources.

---

### Problem Topic

- **Type of Learning**: Unsupervised Learning  
- **Task Type**: Clustering  
- **Objective**: Group countries by development indicators to guide aid distribution  
- **Evaluation Metrics**: Silhouette Score, Davies-Bouldin Index, Domain Interpretability

---

### About the Data

The dataset is obtained from [Kaggle: Unsupervised Learning on Country Data](https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data/data). It contains numerical indicators for countries across various development dimensions.

#### Features Overview:
- **Demographic & Economic**:
  - `Country`: Country name  
  - `GDP`: Gross Domestic Product  
  - `Income`: Net income per person  
  - `Exports`: % of GDP  
  - `Imports`: % of GDP  
  - `Inflation`: Consumer price inflation  
  - `Population`: In millions  

- **Health & Human Development**:
  - `Child Mortality`: Deaths under age 5 per 1,000  
  - `Health`: Govt. health spending as % of GDP  
  - `Life Expectancy`: Average years  
  - `Total Fertility`: Avg. number of children per woman

#### Data Type:
- All features are **numerical**  
- Format: **Tabular**  
- Number of Observations: 160+ countries  

---

> **Source**:  
> Kaggle. (2024). *Unsupervised Learning on Country Data*. Retrieved from https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data/data
