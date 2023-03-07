# Project Name: Lending Club Case Study

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Project Statement

>  The agenda of this project is to identify the driving factors to flag a defaulted loans which are major source of loss for the company.

### Project Background

> This company is the largest **online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures**. Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, lending loans to **‘risky’** applicants is the largest source of financial loss (called credit loss). **Credit loss** is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.
> a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

  -  If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

  -  If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

### Data Set

> The data set is a csv file with the loan data for the Lending Club.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- Major Driving factor which can be used to predict the chance of defaulting and avoiding Credit Loss:
  1. DTI
  2. Grades
  3. Verification Status
  4. Annual income
  5. Pub_rec_bankruptcies
- Other considerations for 'defaults' :
  1. Burrowers from large urban cities like california, new york, texas, florida etc.
  2. Burrowers having annual income in the range 50000-100000.
  3. Burrowers having Public Recorded Bankruptcy.
  4. Burrowers with least grades like E,F,G which indicates high risk.
  5. Burrowers with very high Debt to Income value.
  6. Burrowers with working experience 10+ years.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

- Pandas - version 1.3.4
- NumPy - version 1.20.3
- Seaborn - version 0.11.2
- MatplotLib - version 3.4.3
- Plotly - version 5.7.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.

## Contact

Created by [@sukhijapiyush] - feel free to contact me!

<!-- Optional -->

<!-- ## License -->

## License

This project is open source and available without restrictions.

<!-- You don't have to include all sections - just the one's relevant to your project -->
