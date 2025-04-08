# NFL Machine Learning Analysis
![image](https://github.com/user-attachments/assets/cf430bd1-bea2-4fcd-84c1-85b836586eff)

The attached python analysis was conducted on NFL combine data from 2010 through 2023 that was obtained via Kaggle with a shape of (4,741, 15). The data set consists of 1 integer, 1 boolean, 4 objects, and 9 floats. The data set initially consisted of 11,500 missing entries for 16.17%. KNN imputation was conducted for all the float values to best uphold the integrity and accuracy of the data. The remaining data was imputed with mode to remain consistent in the data set and give realistic findings. To give meaningful insights, the two types of machine learning techniques chosen to analyze the data include K-means clustering and logistic regression. These methods were chosen based on the numerical and binary categorical data available in the data set.

The analysis performed a form of supervised and unsupervised learning in respects to logistic regression and K-means clustering. Meaningful insights were gathered from the K-means analysis regarding 40-yard dash time impacting draft number. Logistic regression was chosen to determine if a player will be drafted based on the data provided. The model utilized many variations of independent variables with the same outcome of low AUC scores below 0.70. While it is disappointing that the logistic regression model isn’t as accurate as expected, it aligns with the uncertainty of the NFL.
