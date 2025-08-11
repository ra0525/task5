<img width="850" height="545" alt="scatter1" src="https://github.com/user-attachments/assets/15c42728-3743-4a72-a639-a099777a5397" /><img width="850" height="545" alt="scatter1" src="https://github.com/user-attachments/assets/ce516dc4-5fb0-4861-81bd-d87920192f09" /># Titanic Dataset — Exploratory Data Analysis (EDA)

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
> Age Distribution
<img width="571" height="453" alt="hist1" src="https://github.com/user-attachments/assets/7f0ff057-9803-4906-9ec8-d70b8d7af6a8"/>

### 2️⃣ Boxplots
> Age vs Pclass
<img width="563" height="453" alt="box" src="https://github.com/user-attachments/assets/7a8498ad-7f27-42ad-b041-5e9034347f49" />

### 3️⃣ Heatmap
>Correlation matrix
<img width="597" height="503" alt="heat" src="https://github.com/user-attachments/assets/37ceb2d0-bc64-45e9-8202-2a5faeecfe49" />

### 4️⃣ Pairplot
<img width="820" height="741" alt="pair" src="https://github.com/user-attachments/assets/7dbdf066-101c-4786-8f2b-b05d15edda86" />
 
### 5️⃣ Scatter Plots
**Scatter 1:** Age vs Fare (Survival-colored)  
<img width="850" height="545" alt="scatter1" src="https://github.com/user-attachments/assets/7b550830-f9ac-47f4-a7ee-07f62af32b93" />

**Scatter 2:** Age vs Fare (Point size = Pclass)  
<img width="1024" height="545" alt="scatter2" src="https://github.com/user-attachments/assets/4e7f6990-f354-45ff-bd66-fdf92253ccec" />

**Scatter 3:** Fare vs Pclass (jittered)  
<img width="887" height="545" alt="scatter3" src="https://github.com/user-attachments/assets/a826f843-7ccc-43e2-9424-ac60267a79fc" />

**Scatter 4:** Fare vs Age (Regression by Survival)  
<img width="843" height="592" alt="scatter4" src="https://github.com/user-attachments/assets/f7879f5d-d284-4c59-a43d-aca51af317b8" />

---

## 📌 Key Findings
- Women and children had higher survival rates.
- 1st class passengers were more likely to survive.
- Higher ticket fares correlated with higher survival probability.
- Younger passengers in higher classes had better survival chances.
- Large families had lower survival rates compared to small families.
