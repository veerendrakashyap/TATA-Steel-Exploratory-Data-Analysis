# TATA-Steel-Exploratory-Data-Analysis

# 📊 Tata Steel Exploratory Data Analysis (EDA)  

## 🔍 Project Overview  
This project performs **Exploratory Data Analysis (EDA)** on Tata Steel's manufacturing data to analyze machine performance, detect anomalies, and identify key factors influencing machine failures. The insights from this analysis can help optimize operations, reduce downtime, and improve production efficiency.  

## 📂 Dataset Information  
The dataset consists of machine operational data collected from Tata Steel’s production units.  
### **Key Features:**
- **Air Temperature [K]** – Measures ambient temperature during operations.  
- **Process Temperature [K]** – Temperature inside the manufacturing process.  
- **Rotational Speed [rpm]** – Speed of machine operation.  
- **Torque [Nm]** – Rotational force applied to machine components.  
- **Tool Wear [min]** – Time a machine tool has been in use.  
- **Machine Failure & Failure Types (TWF, HDF, PWF, OSF, RNF)** – Indicators of machine breakdown causes.  

---

## 📊 Key Steps in the Analysis  
1️⃣ **Data Cleaning & Preprocessing**  
   - Handling missing values and duplicate records.  
   - Converting categorical variables into numerical representations.  
   - Identifying and managing outliers using box plots and IQR.  

2️⃣ **Exploratory Data Analysis (EDA)**  
   - **Univariate Analysis**: Histograms, KDE plots for individual variables.  
   - **Bivariate Analysis**: Scatter plots, correlation heatmaps to identify relationships.  
   - **Multivariate Analysis**: Pair plots to study combined effects of variables.  

3️⃣ **Key Insights**  
   - Machine failures are linked to extreme torque values and high tool wear.  
   - Air temperature and process temperature are strongly correlated.  
   - Outliers in rotational speed and torque indicate potential stress points.  
   - Failure types (TWF, HDF, PWF, OSF, RNF) contribute differently to machine breakdowns.  

---

## 📊 Visualizations & Charts  
This project includes **20+ meaningful visualizations**, such as:  
✔️ **Correlation Heatmap** – Identifies relationships between variables.  
✔️ **Boxplots & Violin Plots** – Detect outliers in machine parameters.  
✔️ **Scatter Plots** – Show the relationship between torque and rotational speed.  
✔️ **Failure Rate Over Time** – Line plot to monitor failures.  
✔️ **Pair Plots** – Multivariate relationships among key variables.  

---

## 🛠️ Tools & Technologies  
- **Python** 🐍  
- **Pandas, NumPy** – Data Cleaning & Analysis  
- **Matplotlib, Seaborn** – Data Visualization  
- **Jupyter Notebook** – Implementation  

---

## 🚀 Business Impact & Recommendations  
✔ **Predictive Maintenance** – Prevent costly machine breakdowns.  
✔ **Process Optimization** – Improve production efficiency by fine-tuning parameters.  
✔ **Cost Reduction** – Early detection of failures reduces downtime.  
✔ **Data-Driven Decision Making** – Helps engineers and managers optimize machine performance.  
