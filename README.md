
# Investigation of Loan Data from Prosper

The prosper data set comprises of loan data of borrowers within a period of time.
The dataset comprises of 81 columns and 113937 rows.
The reason for this investigation is that we are trying to discover the factors that drive the loan outcome of a borrower.




## Installation


    This project was built using python 3.9, using the Jupyter Notebook IDE.
## Overview

The aim of the project was to hone my skills in data visualization. 
Data visualization comprises of two parts: Data Exploration and Data Explanation.
For the exploratory phase, python libraries like pandas and seaborn were used to explore the prosper loan dataset.
Univariate Exploration;
Here, one factor was analyzed at a time.

Bivariate Exploration;
Two factors are analysed thesame time to see their relationships.

Multivariate Exploration;
More than two factors are analysed thesame time to see their relationships.

Afterwhich, I proceeded to the second part of data visualization, Explanatory phase.
This phase, the findings from the datasets were properly arranged for presentation purposes.




## Steps

Step 1: Picking a dataset
For my analysis, the Prosper dataset was used.


Step 2: Data Exploration
The dataset was loaded and explored using panda.
Different graphs were used to explore the dataset.

Step 3: Data Explanation
For this, a slide deck was created for presentation purposes.



## Summary

>The dataset comprises of 113,937 rows and 81 columns.
> 19 columns were picked as choice columns and empty rows were dropped. This brought the rows to 83,397.
> Huge percentage of borrowers are employed.
>Highest income range is $50000 to $74,000.
>From the data, it can be seen that a huge portion of the loans are actually current.
>Loan Rating D had the highest completed rate and also default rate
>Borrowers with Prosper score of 8 had the highest completion rate while those with 6 had the highest default rate
> Category with the highest default rate is debt consolidation
>Borrowers with prosper score of 8 were the most employed. Also, borrowers that are employed tend to have the highest access to loans.


## Key Insights for Presentation

For this project, I tried to discover the drivers for the outcome of a loan transaction at Prosper. My focus was on two outcomes; completed-- which signifies that the borrower paid of the loan obtained from prosper while defaulted signify that the borrower could not pay back his loan to Prosper.
I started by picking 19 columns from the dataset as my columns of choice out of 81 columns contained in the dataset.
These columns were investigated individually. Afterwhich, they were combined to investigate possible relationships (either proportional or inverse) between them. 
from the columns, I concentrated on ProsperScore, IncomeRange, EmploymentStatus, LoanOriginalAmount, Term, ProsperRating (Alpha), and ListingCategory (numeric) as my key independent factors that drove the outcome of loans (LoanStatus).



  