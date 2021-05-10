## Bank loans analysis (Python)

## Project Overview
- Need to know what factors influence the delivery of a loan.
- Need to look for any opportunity to increase the bank's assets.
- It was found that apart from income, family size is an important factor.
- The libraries used were pandas, numpy, matplotlib.pyplot, seaborn and scipy.
- You can access the Jupiter Notebook at this link

## Objectives
Central question:

**What is the most important factor for the delivery of a loan**.

Other questions:
* What is the relationship between education and lending?
* What is the distribution of the client population?
* What types of accounts and insurance do our clients have?
* What is the relationship between income and loans?
* What is the relationship between mortgage and loans?

## Data cleaning and preparation
After importing the libraries we prepared the data for analysis.
- Elimination of negative values and useless columns
- Exploration of the correlation of data and outliers: There is a strong correlation between age and experience

IMAGE OF THE HEAT MAP

- Analysis of the distribution of the data: A large number of outliers were found in income

IMAGE OF HISTOGRAMS AND BOXPLOTS

## EDA
The exploratory data analysis was done with the target questions in mind. Several conclusions were obtained which will be presented below.

- Distribution of client education: The majority of clients are not graduates but it appears that education does not have a direct relationship with lending.

IMAGE

- Analysis of client account type: The vast majority of clients do not have a security or credit account, could generate some extra assets if we find a way to encourage them to seek one.

- Lending in relation to other factors: It seems that the most important factor for a loan is income, no surprise there. Another really important factor is the number of relatives in the family.

## Conclusions
- The most influential values are income and family size.
- The least influential values are age and experience. 
- It is advisable to encourage customers to create a credit account and insurance.
- You can access the code in this link

