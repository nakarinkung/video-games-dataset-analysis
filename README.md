# Video Game Dataset Analysis

## Project Overview
This project explores and analyses a comprehensive video game dataset to uncover key insights and build predictive models.  
It combines data analysis, visualisation, and machine learning to understand video game sales trends.

---

## Goals
1. **Data Exploration** – Understand the dataset structure and contents.  
2. **Data Cleaning** – Handle missing values, inconsistencies, and data types.  
3. **Data Analysis & Visualisation** – Identify key trends, correlations, and sales patterns.  
4. **Sales Prediction Models** – Develop and evaluate machine learning models to predict global sales.  
---

## Project Structure
The analysis is divided into two main parts:

### **PART 1: Exploratory Data Analysis (EDA)**
Answering key business questions:
-  **Which publishers have the highest global sales?**
-  **Which platforms generate the most global sales?**
-  **Which genres dominate global sales?**
-  **What features correlate with high user scores?**

Includes visualisations such as bar charts, heatmaps, and correlation plots.

---

### **PART 2: Advanced Analysis & Machine Learning**

#### **1. Trends Over Time**
- Examine how global video game sales have changed over the years.  
- Identify periods of significant growth or decline.

#### **2. Regional Preferences**
- Compare the popularity of genres and platforms across regions (NA, EU, JP, Others).  
- Analyze cultural and market-based differences in player behaviour.

#### **3. Critic vs. User Scores**
- Explore the relationship between critic ratings and user ratings.  
- Determine whether professional reviews align with player opinions.

#### **4. Machine Learning Applications**
- **Sales Prediction Models:**  
  Use regression algorithms (e.g., Ridge, Lasso, Random Forest) to predict *Global_Sales* based on available features.
  
  **Example result:**  
  - *Best Model:* Ridge Regression  
  - *RMSE:* 1.82 million  
  - *R²:* 0.20  
  → The model captures some predictive power but leaves room for improvement.

---

##  Tools & Technologies
- **Languages:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Models:** Ridge, Lasso, Linear Regression  
- **Visualization:** Matplotlib & Seaborn for charts and plots  

---

##  Key Insights
- Certain publishers and genres dominate global sales (e.g., Nintendo, Action genre).  
- **Sales patterns** show peaks during certain console generations.  
- **Regional differences** highlight distinct gaming preferences.  
- **Critic and user scores** are moderately correlated, suggesting some alignment in opinions.  
- **Sales prediction models** demonstrate moderate accuracy with potential for further improvement through feature engineering.

---

##  Future Work
- Improve model performance with feature selection and data enrichment (e.g., marketing, release timing).  
- Develop a dashboard to visualise results interactively (e.g., with Plotly or Streamlit).

---

##  Dataset
The dataset contains information about:
- Game titles  
- Platforms  
- Release years  
- Publishers  
- Sales (NA, EU, JP, Other, Global)  
- Critic and user scores  
- Genres  

---

