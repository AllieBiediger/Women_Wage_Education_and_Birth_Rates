# Women_Wage_Education_and_Birth_Rates

### Overview: 
For this analysis, we collected data on U.S. births by education level and wage trends over several years. Our approach included four main steps, data cleaning and preparation, exploring trends, applying models and evaluating results for actionable insights. This structure allowed ust to uncover patterns and make informed predictions for future trends.

### Key Findings:
* Wages and Education
  * Higher education levels consistently correlated with higher wages.
  * The Linear Regression model demonstrated the strongest performance in predicting wages with an MSE of 0.3338 and an R-squared of 0.9989.
* Birth Rates and Education
  * Birth rates were generally lower for individuals with higher education levels.
  * Both models struggled to accurately predict birth rates as evidenced by high MSE values with Linear Regression slightly out performing Random Forest.
* Model Comparisons
  * Linear Regression showed greater accuracy for both target variables indicating that simpler models can outperform more complex methods when data trends are relatively linear.
  * Time series predictions for both wages and birth rates were affected by 2020 as an outlier due to the COVID-19 pandemic, introducing variability that the model struggled to accommodate.

### Files:
*“Us_births_2016_2021.csv”* , *“wages_by_education.csv”*
* contains the data sets used for the analysis
  
*“Impact_Womens_Education_Wage_Birth.ipynb”* 
* contains the jupyter notebook code for data cleaning, analysis and modeling
  
*“Impact_Womens_Education_Wage_Birth_Presentation.pdf”* 
* contains the full analysis presentation in powerpoint format

*“Impact_Womens_Education_Wage_Birth_FinalPaper.pdf”*
* contains final paper with visualizations and findings

### Prerequisites:
Python 3.8+
Required Libraries: ‘numpy’, ‘pandas’, ‘matplotlib’, ‘seaborn’, ‘sklearn’, ‘statsmodels’





