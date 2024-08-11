# Customer Churn Analysis for Bank
This project focuses on analyzing customer churn for a bank using Power BI. The goal is to identify key factors that contribute to customer churn and provide insights that can help the bank reduce churn rates and improve customer retention.

## Data Dictionary
#### The dataset includes the following features:
- RowNumber: Record (row) number with no effect on the output.
- CustomerId: Random values that have no effect on customer leaving the bank.
- Surname: The surname of a customer, with no impact on their decision to leave the bank.
- CreditScore: A key factor influencing customer churn. Customers with higher credit scores are less likely to leave the bank.
###### Excellent: 800–850
###### Very Good: 740–799
###### Good: 670–739
###### Fair: 580–669
###### Poor: 300–579
- Geography: The customer's location, which can affect their decision to leave the bank.
- Gender: Explores whether gender plays a role in a customer leaving the bank.
- Age: Relevant factor, as older customers are less likely to leave their bank than younger ones.
- Tenure: Number of years the customer has been a client of the bank. Older clients tend to be more loyal.
- Balance: A good indicator of customer churn. Customers with higher balances are less likely to leave.
- NumOfProducts: Number of products a customer has purchased through the bank.
- HasCrCard: Indicates whether a customer has a credit card.
###### 1: Credit card holder
###### 0: Non-credit card holder
- IsActiveMember: Whether the customer is an active member.
###### 1: Active Member
###### 0: Inactive Member
- Estimated Salary: Customers with lower salaries are more likely to leave the bank compared to those with higher salaries.
- Exited: Indicates whether the customer left the bank.
###### 0: Retain
###### 1: Exit
- Bank DOJ: Date when the customer joined the bank.

## Data Gathering
#### Data was gathered from the following sources:
- ActiveCustomer
- Bank_Churn
- CreditCard
- CustomerInfo
- ExitCustomer
- Gender
- Geography
  
## Churn Analysis
The analysis focused on identifying key factors contributing to customer churn. Understanding these factors helps the bank develop loyalty programs and retention campaigns, ultimately reducing churn rates and increasing customer loyalty.

## Steps Followed
1.	Understanding Business Requirements: Identifying the goals and objectives of the churn analysis.
2.	Data Gathering: Collecting data from various sources to ensure a comprehensive analysis.
3.	Data Cleaning and Transformation: Preparing the data for analysis by cleaning and transforming it.
4.	Data Modelling: Building the data model to support the analysis.
5.	UI Development: Designing and developing the Power BI dashboard to visualize insights and findings.
6.	DAX Functions: Utilizing DAX (Data Analysis Expressions) functions to perform calculations and enhance the analysis.
7.	Row-Level Security: Implementing Row-Level Security (RLS) to restrict data access based on user roles, ensuring that users only see data relevant to them.

