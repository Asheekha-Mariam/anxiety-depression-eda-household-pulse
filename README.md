# Indicators of Anxiety or Depression – Data Analysis Project

##  Project Overview
This project analyzes the **Indicators of Anxiety or Depression Based on Reported Frequency of Symptoms** dataset to identify trends, patterns, and disparities across indicators, phases, states, and demographic subgroups.  
The analysis uses Python for data cleaning, exploratory data analysis (EDA), and visualization to generate meaningful public health insights.

---

##  Dataset
**Source:** Household Pulse Survey – U.S. Census Bureau  
**Domain:** Public Health / Mental Health Analytics  

### Key Columns
- Indicator  
- Group  
- State  
- Subgroup  
- Phase  
- Time Period / Time Period Label  
- Value  
- Low CI  
- High CI  
- Confidence Interval  
- Quartile Range  

---

##  Tools & Libraries Used
- **Python**
- **Pandas & NumPy** – Data cleaning and preprocessing  
- **Matplotlib & Seaborn** – Data visualization  
- **Jupyter Notebook**

---

##  Data Cleaning & Preprocessing
- Loaded CSV data using Pandas
- Identified and handled missing values  
  - Categorical variables: replaced with `NA`  
  - Numerical variables: handled using median where appropriate  
- Removed duplicate records
- Corrected data types (dates and numerical columns)
- Filtered top categories to improve visualization clarity

---

##  Exploratory Data Analysis (EDA)

###  Univariate Analysis
- Distribution of numerical variables using **histograms**
- Outlier detection using **boxplots**
- Frequency analysis of categorical variables (Top-N categories)

###  Bivariate Analysis
- **Numerical vs Numerical:** Scatter plots and correlation analysis  
- **Categorical vs Numerical:** Boxplots and grouped bar charts  

###  Multivariate Analysis
- **Correlation heatmaps** for numerical variables
- **Pivot tables + heatmaps** (State × Subgroup)
- **Grouped bar charts** (Indicator × Phase × Mean Value)
- **3D visualizations** for advanced multivariate insights

---

## Key Insights
- Certain indicators consistently show **higher average anxiety/depression levels**.
- Strong positive relationships exist between **Value, Low CI, and High CI**, confirming statistical consistency.
- Mental health impacts vary significantly across **states and demographic subgroups**.
- Anxiety and depression levels change across phases, indicating **time-dependent effects**.

---

## Conclusion
The analysis highlights meaningful variations in mental health indicators across time, geography, and population segments. These findings emphasize the importance of **targeted, data-driven mental health interventions** rather than uniform approaches.

---

## Future Scope
- Predictive modeling for mental health trends
- Time-series analysis across phases
- Clustering analysis for subgroup identification

---

##  Author
**Asheekha**  
Aspiring Data Analyst  
Python | Data Visualization | Public Health Analytics
