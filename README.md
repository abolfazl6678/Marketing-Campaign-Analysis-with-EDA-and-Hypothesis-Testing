# Marketing-Campaign-Analysis-with-EDA-and-Hypothesis-Testing
Data science project analyzing marketing mix 4Ps (product, price, place, and promotion) using EDA, feature engineering, and hypothesis testing to understand customer acquisition and campaign effectiveness.

## Project Overview ??????  
This project analyzes real-world marketing campaign data to uncover **customer behavior insights** using **Exploratory Data Analysis (EDA)**, **hypothesis testing**, and **statistical modeling**.  
The goal is to evaluate the effectiveness of marketing strategies across the **4Ps (Product, Price, Place, Promotion)** and identify key drivers of **customer acquisition and campaign success**.  

By applying rigorous data analysis, this project demonstrates how **data science can transform marketing decision-making** and help businesses optimize their strategies for better ROI.  

---

## Problem Statement  ????
Marketing campaigns often involve multiple factors such as customer demographics, income levels, purchasing behavior, and promotional channels.  
The challenge is to analyze these dimensions and test hypotheses that explain **why certain campaigns succeed while others fail**.  

As a data scientist, the objective is to:  
- Perform **EDA** to understand customer characteristics and spending habits.  
- Conduct **hypothesis testing** to validate assumptions about campaign effectiveness.  
- Provide **data-driven recommendations** for campaign optimization and customer targeting.  

---

## Dataset Description
This dataset provides insights into **customer demographics, purchasing behavior, and responses to marketing campaigns**. It is designed to support **customer segmentation, targeted marketing, and campaign effectiveness analysis**.

### Available Tables
1. **marketing_data** – complete dataset.  
2. **Data_Dictionary** – description of each variable in the marketing_data table.

### Key Features of the data:  
- **Demographics**: Age, Marital Status, Education, Number of Children  
- **Purchases**: Spending on Wine, Fruits, Meat, Gold, Fish, etc.  
- **Channels**: Web, Catalog, and In-Store transactions  
- **Promotions**: Number of campaigns accepted, complaints, response to last campaign  
- **Country**: Customer’s country of residence 

---

## Steps & Methodology  ??? 

1. **Data Cleaning & Preprocessing**  
   - Handle missing values (e.g., income imputation using education + marital status).  
   - Create new features: Age, Total Children, Total Spending, Total Purchases.  
   - Encode categorical variables using **ordinal encoding** and **one-hot encoding**.  

2. **Exploratory Data Analysis (EDA)**  
   - Histograms & boxplots to detect outliers.  
   - Correlation heatmap to analyze relationships.  
   - Distribution of spending across products and customer groups.  

3. **Hypothesis Testing**  
   - Are older individuals less likely to prefer online shopping?  
   - Do customers with children prefer online shopping due to time constraints?  
   - Is there cannibalization between physical stores and online channels?  
   - Does the United States significantly outperform other countries in purchases?  

4. **Visualization & Insights**  
   - Top-performing products and low-revenue products.  
   - Relationship between age and last campaign acceptance.  
   - Country-level campaign performance.  
   - Spending patterns by number of children.  
   - Education levels among customers with complaints.  

---

## Tools & Technologies  ????
- **Python** (Pandas, NumPy, Scikit-learn, SciPy, Statsmodels)  
- **Visualization**: Matplotlib, Seaborn  
- **Statistical Testing**: T-tests, ANOVA, Chi-square tests  
- **Jupyter Notebook** for analysis  

---

## Key Insights & Outcomes  ???
- Identified **customer segments** most likely to respond positively to campaigns.  
- Detected **spending behavior differences** by demographics and family structure.  
- Validated/Rejected **marketing hypotheses** with statistical rigor.  
- Delivered **data-driven recommendations** to improve campaign ROI and targeting.  

---

## Business Impact  ???
This project highlights how **data-driven insights** can enhance marketing strategies by:  
- Improving **customer segmentation and targeting**  
- Reducing **ineffective marketing spend**  
- Enhancing **promotion channel selection**  
- Driving **customer acquisition and retention**  









