# Machine learning - Kaggle competition




![alt text](https://github.com/jquintanac/ML-Kaggle/blob/main/img/banner.jpg?raw=true)


The goal of the competition is to obtain the lowest RMSE from machine learning predictions of a data jobs.


## Competition bases

* Predict the salary for data Jobs with machine learning
* Data:
  * Salaries_data.csv (Working data)
  * Testeo.csv (Predicting data)
  * Muestra.csv (Example for Kaggle)
* Data will be uploaded to Kaggle and RMSE will be calculated as a score.
* Lowest score wins the competition

## ETL 

* **Salary and salary_currancy**: both were eliminated from the table (salary_in_usd, the column-to-predict, proceed from both).

* **Company location**: Grouped by 'US' or 'Not US'. Too many values to get a good correlation value and to work with.

* **Employee residence**: Grouped by 'US' or 'Not US'. Too many values to get a good correlation value and to work with.

* **Employment type**: Grouped by 'FT' or 'Not FT'. Too many values to get a good correlation value and to work with.

* **Job tittle**: restricted to 'Data Scientist’, 'Data Analyst’, 'Machine Learning Engineer’, 'Research Scientist’ and ‘Other’

* **Categorical to numeric**. With 'get_dummies', I transformed categorical columns to numeric colums to work with them.

Correlation values were improved with these changes.

## Predictions







