Cleaning "Churn" Dataset containing customer demographic information such as Age, Income, 
Zip code and Tenure with the company. This dataset was prepared to analyze information 
on customers who have stayed with the company and those who have left.

The data was explored using the print() function to verify column names and review 
the information within the data set.

The columns relating to customer surveys were renamed for clarity.

The columns were checked for missing values using the isnull() and sum() functions.

Data was cleaned by dropping unnamed columns and imputing missing data using either the
mean, median, or mode depending on the columns distribution.

Outliers were treated using their Z score. The threshold for Z scores was set as 3. 
All outliers with a Z score greater than 3 were removed. 

This project was done for my MS in Data Analytics. 