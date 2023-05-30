# Walmart Weekly Sales Prediction Using Statiscal Methods

## ABSTRACT

This project involves the statistical analysis of Walmart's weekly sales dataset using various methods. The aim of this project is to identify significant trends and patterns in the data that can be used to improve the performance of Walmart stores. The dataset contains information on weekly sales, as well as several other variables such as store size, location, and the presence of special holiday events.The findings from this study will provide valuable insights into the factors that affect Walmart's weekly sales. These insights can be used to make data-driven decisions that can improve the performance of Walmart stores. Furthermore, the methods used in this study can be applied to other retail datasets to gain a better understanding of customer behavior and to improve the efficiency of retail operations. 

## DATASET 

The data used in this project is the Walmart Weekly Sales dataset, obtained from Kaggle (https://www.kaggle.com/datasets/yasserh/walmart-dataset). The dataset consists of 6435 weekly sales records from 45 stores. Each record contains information on the weekly sales, as well as the following features:

1.  Store : The store number
2.  Date : Week of the sales
3.  Weekly_Sales : Sales for the given store
4.  Holiday_Flag : If week is a special holiday week
5.  Temperature : Temperature on sales day
6.  Fuel_Price : Cost of fuel in the region of store
7.  CPI : Customer price index
8.  Unemployment : Prevailing unemployment rate in percentage


Before starting the analysis, the data was explored to identify any issues that could affect the accuracy of the analysis. The first step was to check for missing values, and it was found that there were no missing values in the dataset. However, some of the features, such as temperature and fuel price, had a wide range of values. Therefore, these features were standardized to ensure that they had the same scale as the other features.

After the data cleaning process, the distribution of the weekly sales data was analyzed. A histogram was plotted to visualize the distribution of weekly sales, which showed a skewed distribution. Therefore, the weekly sales data was transformed using the natural logarithm to reduce the skewness and improve the normality of the data.

In addition, the relationships between the features and the weekly sales were explored using scatter plots and pair plots. The scatter plot between weekly sales and store number indicated that some stores had higher sales than others. Therefore, one-hot encoding was performed on the store number feature to perform linear regression effectively later.

Overall, the data was relatively clean and did not require significant preprocessing. The issues that were identified were resolved using standard statistical techniques. The final dataset was used for the subsequent analysis.

## CONCLUSION 

In conclusion, the Walmart dataset was analyzed using various statistical models, revealing that the dataset is non-parametric and not normal. Statistical tests, such as the z test, ANOVA, Turkey, and chi-squared, were conducted to identify the means of different features. Several regression models were fit to the data, including Linear Regression, Ridge Regression, Lasso Regression, Ridge CV, Gradient Booster with hyperparameter tuning, Regularization with Lasso CV, and Polynomial Regression. The best accuracy of 94.31% on the testing set was achieved with Gradient Booster with hyperparameter tuning. Important features were identified using LassoCV and Linear Regression, and Polynomial Regression improved the accuracy to 93.30%. The findings of this analysis have practical implications for Walmart, as accurate sales predictions can inform decisions about inventory, staffing, and advertising.

For more details, please check the [code](https://github.com/nayanikar/walmart-weekly-sales-prediction-using-statiscal-methods/blob/main/Analyzing_Weekly_Sales_in_Walmart_Dataset_Using_Statistical_Models.ipynb) file. 