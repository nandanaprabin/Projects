# Loan Default Risk Analysis
## Project Overview
This project aims to help banks minimize the risk of loan defaults by analyzing customer data such as transaction history, demographic information, loan details, and account characteristics. By identifying patterns in these factors, the bank can predict customers who are likely to default on their loans. The project is based on real anonymized Czech bank data from 1999.

## Objective
The goal of this project is to provide a data-driven approach for banks to assess the financial behavior of customers. By analyzing transaction patterns, loan amounts, and account characteristics, the project aims to identify trends and factors that indicate potential loan defaults. This will help the bank make informed decisions in managing loan portfolios and mitigating risks associated with high-risk clients. Through the visualization of daily transaction amounts and loan distributions, we offer actionable insights into customer behavior, helping to enhance the bank’s loan eligibility assessment process.



## Dataset
The dataset consists of real Czech banking data from 1999, and it includes the following files:

- account.csv – Details of the bank accounts (4500 records)
- card.csv – Information on issued credit cards (892 records)
- client.csv – Client details such as birth number and district (5369 records)
- disp.csv – Describes the relationship between clients and accounts (5369 records)
- district.csv – Demographic information about the districts (77 records)
- loan.csv – Loan details (682 records)
- order.csv – Permanent orders (6471 records)
- trans.csv – Transaction details (1,056,320 records)

## Requirements
To run the project, you need the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install these packages using the command below:
```bash
pip install -r requirements.txt
