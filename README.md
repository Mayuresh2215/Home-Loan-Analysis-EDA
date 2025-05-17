# Home-Loan-Analysis-EDA
**This project aims to analyze bank loan data using Python libraries (Pandas, NumPy, Matplotlib, and Seaborn) to uncover trends, patterns, and key factors influencing loan approvals. Through univariate and bivariate analysis, the project provides insights into customer demographics, loan status distribution, and risk factors.**

- Dataset includes:
  - Demographic data like Gender, Marrital Status,Employee form and Education.
  - Bank related data like ApplicantIncome,CoapplicantIncome, LoanAmount,Dependents and Property_Area.
- Data Preprocessing: Before understanding our data it is very important to clean the data
  - Handling missing/null and duplicate values.
    - In the data there were some null in few columns hence to treat the  null values used "Dropna" function of pandas.
  - Feature Enginerring:
    - Credit History and Loan ID columns have less influence on Loan Amount hence these columns were droped.
- Outliers Check:
  - After using Boxplot for numerical columns it showed that there are outliers in the data.
  - Hence changed IQR i.e interquantarlie range by 1.5 from upper and lower bound.
  - This resulted into removing of outliers
- EDA(Explorlary Data Analysis):
  - Perfromed **Univarient Analysis**
  - Used **Pairplot**
  - Generated **Heatamp** to see correlation.
  - For categorical Columns created **countplots** to understand data distribution.
 
