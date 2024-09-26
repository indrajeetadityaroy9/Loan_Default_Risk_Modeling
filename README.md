# Loan Default Risk Modeling
Predictive regression modeling to estimate the likelihood of borrowers defaulting on loans. By utilizing historical data, such as financial history, loan performance, and employment details, this model provides accurate risk assessments. Use cases include financial institutions making informed lending decisions, reducing potential losses, and improving overall risk management strategies.

### Data Dictionary
| Column Name        | Data Type       | Description                                | Variable Type           |
|--------------------|-----------------|--------------------------------------------|-------------------------|
| User_id            | int             | Unique identifier for the user             | Numerical               |
| Loan Category      | object (String) | Loan category                              | Categorical             |
| Amount             | float           | Loan amount                                | Numerical               |
| Interest Rate      | float           | Interest rate on the loan                  | Numerical               |
| Tenure (years)     | int             | Loan tenure in years                       | Numerical               |
| Employment type    | object (String) | Type of employment                         | Categorical             |
| Tier of Employment | object (String) | Employment tier classification             | Categorical and Ordinal |
| Industry           | object (String) | Industry type                              | Categorical             |
| Role               | object (String) | Job role description                       | Categorical             |
| Work Experience    | object (String) | Category of work experience                | Categorical and Ordinal |
| Total Income (PA)  | float           | Total annual income in monetary value      | Numerical               |
| Gender             | object (String) | Gender of the user                         | Categorical             |
| Married            | object (String) | Marital status                             | Categorical             |
| Dependents         | int             | Number of dependents                       | Numerical               |
| Home               | object (String) | Housing category (owned/rented)            | Categorical             |
| Pincode            | object (String) | Postal code of the user's location         | Categorical             |
| Social Profile     | object (String) | Social profile classification              | Categorical             |
| Is_verified        | object (String) | User's verification status (yes/no)        | Categorical             |
| Delinq_2yrs        | int             | Number of delinquencies in 2 years         | Numerical               |
| Total Payment      | float           | Total payment received by lender           | Numerical               |
| Received Principal | float           | Principal amount received by lender        | Numerical               |
| Interest Received  | float           | Interest amount received by lender         | Numerical               |
| Number of loans    | int             | Number of loans taken by the user          | Numerical               |
| Defaulter          | int             | Indicates if the user is a defaulter (1/0) | Categorical (Binary)    |