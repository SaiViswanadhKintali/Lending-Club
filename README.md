# Project Name: Lending Club Case Study

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Project Statement

Identify the driving factors to flag defaulted loans, which may lead to a financial loss for the company.

### Project Background

A consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

* If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
* If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

When a person applies for a loan, there are two types of decisions that could be taken by the company:

* Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
	* Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
	* Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
	* Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 
* Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

### Data Set

The data set is a csv file with the loan data for the Lending Club. Filename - "loan.csv"

## Conclusions

1. Lending club Should consider/ focus more on DTI during the loan process. As Charge-off loan% is increasing with the increase in DTI ratio.
2. Majority of the loans which are defaulted are from grades B, C ,D. So loans under these categories need more focus.
3. Loans for Small business/ Renewable Energy have high charge-off rate. So loans for these purposes need more focus.
4. Loans having higher interest rates have more defaulters. Hence, check the background of applicant thoroughly , if the interest rate is high.
5. Cities like CA, NY which high number of loans as well as high charged-off/ defaulted loans.
6. The charged-off rate is very high in long-term loans (60 months), almost double to short-term loans. So Long term loans have high risk.
7. Clients with Bankruptcies have a high chance of default/ Charged-off loan.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

- Pandas - version 1.4.2
- NumPy - version 1.21.5
- Seaborn - version 0.11.2
- MatplotLib - version 3.5.1
- plotly - version 5.6.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

Created & Owned by Sai Viswanadh Kintali & Sanskriti Agarwal 
