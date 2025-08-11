# Titanic Dataset — Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis** on the Titanic dataset to identify **patterns, trends, and relationships** between passenger features and survival outcomes.  
The goal is to practice **data exploration** using **Pandas, Matplotlib, and Seaborn** in Python.

---

## 📂 Dataset
- **File:** `train.csv`  
- **Source:** [Titanic Dataset](https://www.kaggle.com/c/titanic/data?select=train.csv&utm_source=chatgpt.com)  
- **Description:** Contains passenger demographics, ticket details, and survival status.

---

## 🔍 Analysis Steps
1. **Data Loading & Inspection**
   - Used `.head()`, `.info()`, `.describe()`, and `.value_counts()` to understand dataset structure.
   
2. **Missing Value Handling**
   - Checked for `NaN` values and decided on imputation or removal.

3. **Statistical Summary**
   - Generated numerical summaries to detect outliers and central tendencies.

4. **Data Visualization**
   - **Histograms:** Distribution of numerical features.
   - **Boxplots:** Detect outliers and compare distributions across categories.
   - **Scatter Plots:** Explore relationships between variables.
   - **Heatmap:** Correlation matrix of numerical features.
   - **Pairplot:** Visualize multiple variable relationships.

5. **Observations**
   - Added Markdown notes for each plot to explain patterns and anomalies.

6. **Summary of Findings**
   - Compiled final insights about survival factors.

---

## 📊 Visualizations Used

### 1️⃣ Histograms
![Age Distribution](images/hist_age.png)  
![Fare Distribution](images/hist_fare.png)  

### 2️⃣ Boxplots
![Age vs Survival](images/box_age_survival.png)  
![Fare vs Survival](images/box_fare_survival.png)  

### 3️⃣ Heatmap
![Correlation Heatmap](images/heatmap.png)  

### 4️⃣ Pairplot
![Pairplot of Key Features](images/pairplot.png)  

### 5️⃣ Scatter Plots
**Scatter 1:** Age vs Fare (Survival-colored)  
![Scatter 1](images/scatter_age_fare_survival.png)  

**Scatter 2:** Age vs Fare (Point size = Pclass)  
![Scatter 2](images/scatter_age_fare_pclass.png)  

**Scatter 3:** Fare vs Pclass (jittered)  
![Scatter 3](images/scatter_fare_pclass.png)  

**Scatter 4:** Fare vs Age (Regression by Survival)  
![Scatter 4](images/scatter_regression_fare_age.png)  

---

## 📌 Key Findings
- Women and children had higher survival rates.
- 1st class passengers were more likely to survive.
- Higher ticket fares correlated with higher survival probability.
- Younger passengers in higher classes had better survival chances.
- Large families had lower survival rates compared to small families.
