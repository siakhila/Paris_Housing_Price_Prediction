# Paris_Housing_Price_Prediction

**Project Title**: Paris Housing Price Prediction  

---

#### **Description**  
This project focuses on analyzing and predicting housing prices in Paris using a dataset that includes various property features such as size, amenities, and neighborhood attributes. The goal is to identify key factors that influence property prices and provide actionable recommendations for property development and marketing strategies. The analysis involves data cleaning, exploratory data analysis (EDA), feature selection, and linear regression modeling to predict property prices.

---

#### **Key Features**  
- **Data Cleaning**: Handling missing values, removing irrelevant columns, and addressing outliers.  
- **Exploratory Data Analysis (EDA)**: Testing hypotheses related to property features and their impact on prices.  
- **Feature Selection**: Using correlation matrices and Variance Inflation Factor (VIF) to select the most relevant features.  
- **Model Development**: Building and evaluating linear regression models to predict property prices.  
- **Business Recommendations**: Providing insights on which property features to focus on to maximize value.  

---

#### **Files**  
- **`Paris_housing_Price_Prediction.ipynb`**: Jupyter notebook containing the code for data cleaning, EDA, model development, and evaluation.  
- **`Paris_housing_Price_Prediction.docx`**: Detailed report summarizing the analysis, findings, and recommendations.  
- **`Paris_housing_Price_Prediction.csv`**: Dataset used for the analysis.  

---

#### **Requirements**  
- **Python 3.x**
- **Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn, statsmodels, plotly

---

#### **Results**  
- **Key Findings**:  
  - **Property Size (`squaremeters`)**: The most significant predictor of property prices.  
  - **Amenities**: Features like pools (`hasPool`) add to the property's appeal but have a lesser impact on price compared to size.  
  - **Neighborhood Attributes**: Factors like `cityPartRange` showed limited impact on property prices in this dataset.  

- **Model Performance**:  
  - The final linear regression model achieved an **R-squared value of 0.874**, indicating strong explanatory power.  
  - Property size (`squaremeters`) was the only statistically significant predictor of price.  

---

#### **Conclusion**  
The analysis revealed that **property size** is the primary driver of housing prices in Paris, while other features like pools and neighborhood attributes had minimal impact. Based on these findings, the following recommendations are made:  
1. **Focus on Property Size**: Prioritize developing larger properties to command higher prices.  
2. **Enhance Amenities**: Consider adding appealing features like pools to attract premium buyers.  
3. **Targeted Marketing**: Use insights from the analysis to tailor marketing strategies to buyer preferences.  

---

#### **Contributors**  
- **Akhila Singaraju**  
