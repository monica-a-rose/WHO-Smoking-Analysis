# Analysis of WHO Data on Smoking & Mortality Risk

### Project Goal
This project analyzes a WHO dataset of over 110,000 records to model the key drivers of NCD mortality risk. The analysis progresses from data cleaning and advanced imputation to building and comparing OLS and Random Forest models, culminating in a scenario analysis to forecast the public health impact of smoking reduction policies.

---

### Key Findings & Highlights

*   **Advanced Data Cleaning:** Successfully implemented a full data pipeline, using **Multivariate Imputation by Chained Equations (MICE)** to robustly handle missing values and correct for biases that simpler methods would have introduced.

*   **Strategic Modeling:** Progressed from an initial OLS regression to a more powerful **Random Forest** model after diagnostic checks revealed significant non-linearity in the data.

*   **Actionable Insights:** The final, cross-validated Random Forest model (**Mean CV R² = 0.55**) was used to forecast that a **10% reduction in smoking prevalence could lower mortality risk by 3.9%** for males in upper-middle-income nations, identifying a key demographic for targeted health interventions.

---

### Technology Used
*   **Python**
*   **Libraries:** Pandas, scikit-learn, statsmodels, Matplotlib, Seaborn