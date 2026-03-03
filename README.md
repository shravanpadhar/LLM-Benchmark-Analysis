# LLM Frontier Wars 2025-2026: Multi-Model Segmentation & Benchmark Prediction
## A Comprehensive Study of Benchmarks, Pricing, and Model Performance
---
<p align="center">
  <img src="header.png" alt="LLM Frontier Wars Header Image" width="100%">
</p>

---
## 🚀  Project Overview
In the rapidly evolving landscape of Artificial Intelligence, the "Benchmark Wars" are no longer just about raw power, but about the delicate balance between **reasoning capabilities, inference speed, and cost-efficiency**. 

This project provides a comprehensive, data-driven analysis of **24 frontier Large Language Models (LLMs)** released between 2024 and 2026. By acting as a Senior Machine Learning Engineer, I have performed rigorous Exploratory Data Analysis (EDA), unsupervised clustering to segment the market, and predictive modeling to identify the core drivers of AI intelligence.

**Goal:** To help developers and researchers make informed decisions by identifying the best-performing models per dollar and predicting overall benchmark success based on architectural specifications.

---

## 🛠 Project Structure & Notebook Breakdown

###  Exploratory Data Analysis (EDA)
* **Data Cleaning:** Handled missing values in parameter counts via context-aware median imputation and converted release periods into `datetime` objects.
* **Univariate Analysis:** Analyzed the distribution of the `overall_benchmark_avg` to identify performance density.
* **Bivariate Analysis:** Explored the relationship between **Performance per Dollar** and **Total Intelligence**, highlighting the high-value quadrant (dominated by DeepSeek).
* **Global Insights:** Visualized the "AI Race" comparing the USA, China, and France.

### Feature Engineering & Clustering
* **Preprocessing:** Implemented `LabelEncoding` for categorical tiers (Speed, Price, Context) and `StandardScaler` for numerical normalization.
* **Unsupervised Learning:** Applied **K-Means Clustering**.
    * Used the **Elbow Method** to determine the optimal $K=3$.

    * **Segmentation:** Grouped models into "Frontier Reasoners," "High-Efficiency Workers," and "Budget/Fast" tiers.

### Predictive Modeling
* **Algorithms:** Evaluated Linear Regression, Ridge, Lasso, Random Forest, and Gradient Boosting.
* **Metrics:** Focused on $R^2$, MAE, and RMSE to ensure high-fidelity predictions.
* **Interpretability:** Used Random Forest feature importance to rank which benchmarks (e.g., GPQA Diamond vs MMLU) actually move the needle for a model's rank.


##  Key Insights
* **Open Source Parity:** Open-source models have effectively closed the gap, with median performance now matching proprietary models.
* **Intelligence Correlation:** There is a strong linear correlation between general knowledge (MMLU) and software engineering (SWE-Bench), suggesting coding ability is a byproduct of high-tier reasoning.
* **Pricing Strategy:** Across all providers, output tokens are consistently priced 4x to 5x higher than input tokens.

---

##  Technologies Used
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-%234479A1.svg?style=for-the-badge&logo=Seaborn&logoColor=white)

---
##  Dataset Information
 * **Dataset:** [LLM Benchmark Wars 2025-2026 | 24 Models Compared](https://www.kaggle.com/datasets/alitaqishah/llm-benchmark-wars-2025-2026-24-models-compared)
* **Size:** 24 Models across 31 features.
* **Key Features:** MMLU, HumanEval, GPQA Diamond, SWE-Bench, AIME 2025, Pricing (Input/Output), Speed (Tokens/sec), and Context Window.

---

## 🏁 Getting Started

### Prerequisites
To run this project locally, install the required dependencies:
```bash
pip install pandas numpy seaborn matplotlib scikit-learn kagglehub
```
---

##  License & Credits

* **Dataset:** Created by [Ali Taqishah](https://www.kaggle.com/alitaqishah) under Open Data License.
* **Notebook Author:** [Shravan Padhar](https://www.kaggle.com/shravanpadhar) 
* **References:**  Data compiled from Artificial Analysis, LMSYS Chatbot Arena, and official technical reports.

##  Connect with Me
If you found this analysis helpful, feel free to reach out or star the repo!
* **Kaggle:** [Shravan Padhar](https://www.kaggle.com/shravanpadhar) 
* **LinkedIn:** [Shravan Padhar](https://www.linkedin.com/in/shravanpadhar/) 
