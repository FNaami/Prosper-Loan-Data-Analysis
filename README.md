# Exploration Data Analysis of Loan Data from Prosper
## by Felix Ehoneah Naami


## Dataset

> The Prosper loan data set, made available by Udacity as a requirement for the final project of their Nanodegree program, comprises 113,937 loans, each containing 81 variables. These variables include information such as loan amount, borrower rate (interest rate), current loan status, borrower income, and numerous others.
The dataset can be found [here](https://www.google.com/url?q=https://www.google.com/url?q%3Dhttps://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv%26amp;sa%3DD%26amp;ust%3D1581581520570000&sa=D&source=editors&ust=1677706425947762&usg=AOvVaw1RCUjXcSlITmmQLJd8vVWN) and the data dictionary explaining the various variables in the data set can also be found [here](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&source=editors&ust=1677706425948414&usg=AOvVaw0wLEVbH6AdpVkYb4w0Sq0P).


## Summary of Findings

>Borrower rate has a unimodal distribution with a peak around 0.15. A steep increase in frequency occurs after 0.30, indicating that a significant portion of borrowers receive interest rates above this value. There were no unusual points detected in the distribution of borrower rates, and no need to perform any data transformations.

>Stated monthly income and debt-to-income ratio distributions are right-skewed, meaning there were more borrowers with lower incomes and higher debt-to-income ratios. However, this skewness did not significantly affect the analysis, and the data was considered suitable for further analysis without any transformations.

>Borrower rate has a negative association with loan original amount, and borrowers with prestigious occupations tend to receive lower rates. Employment status is also an important factor when evaluating a borrower's creditworthiness. There is a weak negative correlation between borrower rate and stated monthly income, home ownership, and verification of income.

>There is a positive correlation between loan amount and borrowers' stated monthly income, and the majority of borrowers in the dataset own a home, regardless of their employment status. These relationships provide insight into the factors that lenders consider when evaluating a borrower's creditworthiness.

>The negative relationship between borrower rate and loan amount becomes slightly positive when Prosper score increases. As Prosper score improves, the loan amount for all three terms increases, with a greater difference in loan amount between terms. Borrower rate decreases as the borrowing term increases for individuals with Prosper scores 1-5, but increases with the term for those with scores 9-10.


## Key Insights for Presentation

>Borrower rate has a unimodal distribution with a peak around 0.15. A steep increase in frequency occurs after 0.30, indicating that a significant portion of borrowers receive interest rates above this value.

>Borrower rate has a negative association with loan original amount, and borrowers with prestigious occupations tend to receive lower rates.

>There is a positive correlation between loan amount and borrowers' stated monthly income, and the majority of borrowers in the dataset own a home, regardless of their employment status.

>The negative relationship between borrower rate and loan amount becomes slightly positive when Prosper score increases. As Prosper score improves, the loan amount for all three terms increases, with a greater difference in loan amount between terms.

>Borrower rate decreases as the borrowing term increases for individuals with Prosper scores 1-5, but increases with the term for those with scores 9-10.