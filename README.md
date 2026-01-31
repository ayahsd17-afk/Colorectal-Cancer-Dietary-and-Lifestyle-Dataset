# Data-Driven Health Insights  
Correlation Analysis and Hypothesis Testing on Health and Lifestyle Factors
https://www.kaggle.com/datasets/ziya07/colorectal-cancer-dietary-and-lifestyle-dataset?select=crc_dataset.csv

##  Project Overview
This project analyzes how lifestyle behaviors—such as smoking, exercise habits, and dietary patterns—relate to health indicators including BMI,and cholesterol levels.  
Through exploratory data analysis (EDA), hypothesis testing, and correlation analysis, the project aims to identify factors that influence health outcomes based on real-world data.

---

##  Objectives
- Understand basic statistics and distributions of the dataset (EDA)
- Conduct hypothesis testing using t-tests, z-tests, and ANOVA
- Perform correlation analyses using Pearson, Spearman, Kendall’s Tau, Point-Biserial, and Phi coefficient
- Visualize results and summarize real-world implications

---

##  Dataset
Source of dataset:  
Kaggle

Main variables:
- BMI  
- Smoking status  
- Exercise frequency   
- Cholesterol levels  
- Daily calorie intake  

---

##  Exploratory Data Analysis (EDA)
Tasks performed:
- Summary statistics (mean, median, standard deviation)
- Distribution checks using histograms and boxplots
- Missing value inspection
- Outlier detection# Colorectal-Cancer-Dietary-and-Lifestyle-Dataset

 ---

### Hypothesis Testing

To examine how lifestyle behaviors influence health indicators, a one-way ANOVA was conducted to evaluate differences in BMI across lifestyle groups.

### Test Performed

One-way ANOVA: BMI across lifestyle groups 
The analysis assessed how BMI varied based on lifestyle categories.  
The results showed:

    F = 0.914, p = 0.434

No statistically significant differences were observed among the lifestyle groups.  
→ This suggests that the lifestyle categories used in this dataset may not sufficiently explain variations in BMI.

---

### Correlation Analysis

To understand how lifestyle, body composition, and age relate to colorectal cancer risk (CRC_Risk), the associations between variables were evaluated using Kendall’s rank correlation coefficient (τ).

### Key Findings

Lifestyle × CRC_Risk

    τ = 0.256, p = 1.84e−16 
    → Individuals with poorer lifestyle scores tended to have higher colorectal cancer risk.

BMI × CRC_Risk

    τ = 0.236, p = 8.63e−20
    → Higher BMI was significantly associated with increased CRC risk.

Age × CRC_Risk

    τ = 0.164, p = 2.88e−10
    → CRC risk increased with age, although the association was weaker than those of lifestyle or BMI.

---

### Interpretation

・Lifestyle, BMI, and age were all significantly associated with colorectal cancer risk.

・ The strength of association followed the order: Lifestyle > BMI > Age, indicating that lifestyle factors had the strongest relationship with CRC risk.

・ANOVA results showed no BMI differences across lifestyle groups,  
    → suggesting that the influence of lifestyle on CRC risk may operate independently of BMI rather than through BMI as a mediating factor.

