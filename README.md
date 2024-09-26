# Loan Default Risk Modeling
Predictive regression modeling to estimate the likelihood of borrowers defaulting on loans. By utilizing historical data, such as financial history, loan performance, and employment details, this model provides accurate risk assessments. Use cases include financial institutions making informed lending decisions, reducing potential losses, and improving overall risk management strategies.

### Data Dictionary
| Column Name          | Data Type                | Description                            | Variable Type             |
|----------------------|--------------------------|----------------------------------------|---------------------------|
| User id              | Integer                  | Unique user identifier                 | Numerical                 |
| Loan category        | String                   | Loan category                          | Categorical               |
| Amount               | Integer                  | Loan amount                            | Numerical                 |
| Interest Rate        | Integer                  | Interest rate on the loan              | Numerical                 |
| Tenure               | Integer                  | Loan tenure in months/years            | Numerical                 |
| Employment type      | String                   | Type of employment                     | Categorical               |
| Tier of Employment   | String                   | Employment tier classification         | Categorical and Ordinal   |
| Industry             | String                   | Industry type                          | Categorical               |
| Role                 | String                   | Job role description                   | Categorical               |
| Work Experience      | String                   | Category of work experience            | Categorical and Ordinal   |
| Total Income         | Integer                  | Total annual income                    | Numerical                 |
| Gender               | String                   | Gender of the user                     | Categorical               |
| Married              | String                   | Marital status                         | Categorical               |
| Dependents           | Integer                  | Number of dependents                   | Numerical                 |
| Home                 | String                   | Housing category (owned/rented)        | Categorical               |
| Social Profile       | String                   | Social profile classification          | Categorical               |
| Is_verified          | String                   | User's verification status (yes/no)    | Categorical               |
| Delinq_2yrs          | Integer                  | Number of delinquencies in 2 years     | Numerical                 |
| Total Payment        | Integer                  | Total payment received by lender       | Numerical                 |
| Received Principal   | Integer                  | Principal amount received by lender    | Numerical                 |
| Interest Received    | Integer                  | Interest amount received by lender     | Numerical                 |
| Number of loans      | Integer                  | Number of loans taken by the user      | Numerical                 |
| Defaulter            | String                   | Indicates if the user is a defaulter   | Categorical               |

