# EDA_PROJECT22BDS0267
BCSE331L EDA submissions

#  BCSE331L – Exploratory Data Analysis (EDA) Project

**Reg. No.**: 22BDS0267  
**Course**: BCSE331L – Exploratory Data Analysis (TH)  
**CO5**: Apply Techniques for handling multi-dimensional data  

---

##  Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the dataset `econmath.csv` provided for the BCSE331L course.  
The aim is to clean, analyze, and visualize the dataset to identify trends, patterns, and correlations between variables.

The project includes:
- **Data Dimensions**
- **Summary Statistics**
- **Data Handling & Cleaning**
- **Univariate Analysis**
- **Bivariate Analysis**
- **Multivariate Analysis**  
(using Python in Google Colab)

***********************************************************************
# Phase 2 – Data Summarization and Visualization

## Project Overview
In this phase of my project, I performed **statistical summarization, visualization, and clustering** on the student performance dataset.  
The main target variable I focused on was **`score`**, which represents the overall performance of students.

---

## Steps I Performed

1. **Statistical Summary Measures**  
   - Calculated **skewness** to check the symmetry of distributions.  
   - Calculated **quantiles (5%, 25%, 50%, 75%, 95%)** to understand spread and variability.  

2. **1D Analysis**  
   - Plotted **histograms, KDE plots, bar plots, and dot plots**.  
   - Explored the distribution of each numerical and categorical variable.  
   - Observed that study/work hours were skewed, GPAs were close to normal, and attendance leaned towards higher values.  

3. **2D Analysis**  
   - **Scatterplots**: GPA (`colgpa`) and ACT scores (`act`, `actmth`) showed positive correlation with `score`.  
   - **Boxplots**: Females scored slightly higher than males; students with calculus and good attendance had better scores.  
   - **Heatmaps**: Showed relationships like consistency in father and mother college education.  

4. **3D Analysis**  
   - Created a **boxplot with hue** (Male vs Calculus vs Score).  
   - Found that students who had taken calculus scored higher, regardless of gender.  

5. **Clustering (Module 5)**  
   - Applied **Agglomerative Hierarchical Clustering**.  
   - Formed **3 clusters of students**: high achievers, medium performers, and low performers.  
   - Visualized with a dendrogram and a cluster vs score boxplot.
  
# Phase 3 – Dimensionality Reduction and Model Evaluation

## Project Overview
In this phase, I focused on applying **PCA (Principal Component Analysis)** to reduce the dataset’s dimensions, building **regression models**, and evaluating their performance.

---

## Steps Performed

1. **Dimensionality Reduction (PCA):**  
   - Reduced features while retaining 95% of the data variance.  
   - Visualized data in 2D using the first two principal components.

2. **Model Building:**  
   - Built two regression models – **Linear Regression** and **Random Forest Regressor**.  
   - Used 80% of the data for training and 20% for testing.

3. **Model Evaluation:**  
   - Compared models using **R²**, **RMSE**, and **MAE** metrics.  
   - Linear Regression performed the best with R² = 0.39.  
   - Random Forest performed slightly lower, indicating mostly linear relationships in data.

---

## Key Insights
- PCA reduced complexity while maintaining major data patterns.  
- Linear Regression (without PCA) gave the most accurate predictions.  
- Actual vs Predicted plots showed a clear positive trend between predicted and true scores.

---

## Conclusion
Phase 3 helped me understand how dimensionality reduction and regression modeling work together.  
I learned how to evaluate models and identify the best-performing one for predicting student performance.

