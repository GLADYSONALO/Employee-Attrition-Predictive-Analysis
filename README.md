# Employee-Attrition-Predictive-Analysis
Predictive HR analytics project analyzing employee attrition across onsite, hybrid, and remote work models using Python and Power BI. Combines machine learning insights with interactive dashboards to reveal key workforce and retention trends.
## 📋 Overview
This project investigates the **predictive factors influencing employee attrition** across **onsite, hybrid, and remote** work models.  
It combines **machine learning analysis using Python** with **data visualisation in Power BI** to explore how work models, tenure, grade level, and demographic factors contribute to attrition patterns.

To the best of my knowledge, this research is the **first comparative study** that combines predictive algorithms and work-model segmentation to identify differences in attrition drivers.

---

## Objectives
- Analyse key predictors of employee attrition across three work models: **onsite, hybrid, and remote**.  
- Apply and compare multiple machine learning algorithms to assess predictive performance.  
- Identify which features are most influential for each work model.  
- Create **interactive Power BI dashboards** to communicate insights effectively.

---

## Tools & Technologies
- **Programming:** Python (pandas, scikit-learn, numpy, matplotlib, seaborn)  
- **Visualisation:** Power BI (for dashboard design and reporting)  
- **Data Source:** Publicly available HR dataset  
- **Methods:** Data cleaning, feature engineering, classification modelling, and comparative performance evaluation  

---

## Machine Learning Models Used
| Algorithm | Description | Key Findings |
|------------|--------------|---------------|
| Logistic Regression | Baseline model for binary classification | Good interpretability but limited non-linear performance |
| Decision Tree | Hierarchical segmentation based on feature importance | Helped visualise decision paths for attrition |
| K-Nearest Neighbours (KNN) | Distance-based model | Moderate accuracy; sensitive to data scaling |
| Support Vector Machine (SVM) | High-dimensional classification | Performed well on balanced data |
| **Random Forest** | Ensemble learning model | **Best overall performance** across all work models (highest accuracy and F1-score) |

---

## Results Summary
- **Random Forest achieved the best predictive accuracy** across all work-model scenarios.  
- Key predictive factors included **Work Model**, **Tenure**, **Job Grade**, **Age Group**, and **Marital Status**.  
- **Hybrid employees** showed higher attrition variability, suggesting role flexibility influences retention patterns.  

---

## Power BI Dashboards

### 1️⃣ Workforce Overview  
Provides a summary of workforce composition and key metrics such as total employees, attrition, average age, and tenure.

![Workforce Overview](./HR_Dashboard_page-0001.jpg)

---

### 2️⃣ Workforce Demography  
Displays demographic breakdowns across departments, including gender, age, marital status, grade level, and tenure bands.

![Workforce Demography](./HR_Dashboard_page-0002.jpg)

---

### 3️⃣ Attrition Demography  
Highlights attrition by work model, job grade, age, gender, and tenure — visually linking demographic insights to attrition trends.

![Attrition Demography](./HR_Dashboard_page-0003.jpg)

---

## Key Insights
- The **work model** is a significant predictor of attrition across employee groups.  
- Attrition is highest among employees with **0–2 years tenure** and **mid-level positions**.  
- Visual dashboards enable HR leaders to **pinpoint retention risks** and design targeted interventions.  

---

## Research Impact
This project demonstrates how **data science and people analytics** can inform HR strategy.  
By combining machine learning with business intelligence tools, organisations can make data-driven workforce decisions that improve engagement and reduce turnover.

---

## Author
**Gladys Uyo Onalo**  
MSc Business Analytics | Data Analyst | Power BI | SQL | Python  
📧 gladonalo@gmail.com  
🔗 [www.linkedin.com/in/gladys-onalo-1499a257]
