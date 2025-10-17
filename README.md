# Analysis of WHO Data on Smoking & NCD Mortality Risk

> This project analyzes a WHO dataset to model the drivers of NCD mortality risk and forecast the public health impact of smoking reduction policies.

---

### ➡️ [**Click Here to View the Full Project Notebook**](WHO_Smoking_Mortality_Analysis.ipynb)

---

## Key Features & Insights

*   **Advanced Data Imputation:** Implemented a full data pipeline using **Multivariate Imputation by Chained Equations (MICE)** to robustly handle missing values, correcting for biases that simpler methods would have introduced.

*   **Strategic Modeling:** Progressed from an initial OLS regression to a more powerful **Random Forest** model after diagnostic checks revealed significant non-linearity in the data.

*   **Actionable Forecast:** The final, cross-validated Random Forest model (**Mean CV R² = 0.55**) was used in a scenario analysis to forecast that a **10% reduction in smoking prevalence could lower mortality risk by 3.9%** for males in upper-middle-income nations.

## Technologies Used
- **Python:** scikit-learn, pandas, statsmodels
- **Visualization:** Matplotlib, Seaborn

## Dataset

This project uses publicly available data on non-communicable diseases (NCDs) and their risk factors, sourced from the **World Health Organization (WHO) Global Health Observatory**.

---

## Results

The scenario analysis using the final Random Forest model predicted that a 10% reduction in smoking could lower mortality risk for males in upper-middle-income countries by as much as **3.9%**.
