# 🧬 Life Expectancy Analysis

## 📖 Overview

This project explores the socio-economic, health, and demographic factors influencing **life expectancy across countries**. Using data analysis and visualization techniques, the goal is to identify key drivers of life expectancy and uncover how different variables — such as GDP, healthcare expenditure, education, and immunization rates — correlate with public health outcomes.

The analysis combines **data cleaning, statistical modeling, and visual exploration** to provide actionable insights into global health development patterns.

---

## 🧩 Dataset

The dataset contains multiple indicators for various countries, including:

* Life expectancy (target variable)
* GDP and income composition
* Schooling years
* Healthcare expenditure
* Mortality and immunization rates
* Population and status (developed vs developing)

**Source:** WHO & UN data repositories (often distributed via Kaggle’s *Life Expectancy (WHO)* dataset).

---

## ⚙️ Methodology

1. **Data Cleaning**

   * Handled missing values through imputation or removal based on feature significance.
   * Normalized numerical variables for consistency.
   * Encoded categorical features such as “Status” (Developed / Developing).

2. **Exploratory Data Analysis (EDA)**

   * Examined distributions, correlations, and pairwise relationships.
   * Used heatmaps and scatter plots to highlight high-impact predictors.
   * Detected outliers and assessed variable interactions.

3. **Feature Engineering**

   * Derived new metrics such as healthcare expenditure per capita ratio.
   * Standardized schooling years and GDP scales for comparability.

4. **Modeling and Evaluation**

   * Applied regression models (Linear Regression, Random Forest, etc.) to predict life expectancy.
   * Evaluated models using R², RMSE, and residual diagnostics.

5. **Visualization**

   * Used Matplotlib and Seaborn for comparative visualization across countries and regions.

---

## 📊 Results and Analysis

* **Strongest Predictors:**

  * Adult Mortality (negative correlation)
  * Schooling (positive correlation)
  * Income Composition of Resources (positive correlation)
  * BMI and GDP per capita also showed moderate influence

* **Developing vs Developed:**

  * Developed countries have higher life expectancy and lower variance.
  * In developing countries, improvements in healthcare expenditure and education yield stronger relative gains.

* **Model Performance:**

  * Random Forest achieved the highest R² (~0.95), indicating robust predictive capability.
  * Linear Regression captured broad trends but struggled with outliers and non-linear relationships.

* **Key Insights:**

  * **Education and economic stability** are consistent drivers of longevity.
  * Preventable causes (e.g., infant mortality, disease immunization rates) heavily impact life expectancy in lower-income regions.
  * Investment in healthcare and education correlates more strongly with life expectancy than GDP alone.

---

## 🧠 Conclusions

Life expectancy is a multi-factor outcome shaped by both direct (healthcare) and indirect (education, income) influences.
Policies focusing on **education access, healthcare investment, and poverty reduction** have the most measurable impact on improving national longevity.

---

## 🧰 Tools & Libraries

* **Python**
* **Pandas**, **NumPy** — data manipulation
* **Matplotlib**, **Seaborn** — visualization
* **Scikit-learn** — modeling and evaluation
* **Jupyter Notebook** — analysis environment

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone <repo-url>
   cd life_expectancy_analysis
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:

   ```bash
   jupyter notebook Life_Expectancy.ipynb
   ```
4. Run all cells sequentially to reproduce results.

---

## 📈 Future Work

* Extend analysis to **time-series forecasting** of life expectancy trends.
* Include **regional clustering** to detect health policy similarities.
* Experiment with **causal inference** or **SHAP-based feature attribution** for interpretability.

---

## 🧾 Author

**Huru Algayeva**
Data Scientist / ML Engineer
