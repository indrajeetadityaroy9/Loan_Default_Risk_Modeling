# Loan Default Risk Modeling
Predictive regression modeling to estimate the likelihood of borrowers defaulting on loans. By utilizing historical data, such as financial history, loan performance, and employment details, this model provides accurate risk assessments. Use cases include financial institutions making informed lending decisions, reducing potential losses, and improving overall risk management strategies.

### Data Dictionary
| Column Name          | Data Type                | Description                   |
|----------------------|--------------------------|-------------------------------|
| User id              | Integer                  | Unique user identifier        |
| Loan category        | String                   | Categorical variable          |
| Amount               | Integer                  | Loan amount                   |
| Interest Rate        | Integer                  | Interest rate                 |
| Tenure               | Integer                  | Loan tenure                   |
| Employment type      | String                   | Categorical variable          |
| Tier of Employment   | Categorical and Ordinal  | Employment tier classification|
| Industry             | Categorical              | Industry type                 |
| Role                 | Categorical              | Role description              |
| Work Experience      | Categorical and Ordinal  | Work experience category      |
| Total Income(PA)     | Integer                  | Total annual income           |
| Gender               | Categorical              | Gender of the user            |
| Married              | Categorical              | Marital status                |
| Dependents           | Integer                  | Number of dependents          |
| Home                 | Categorical              | Housing category              |
| Pincode              | Unknown                  | Pincode information           |
| Social Profile       | Categorical              | Social profile of the user    |
| Is_verified          | Categorical              | Verification status           |
| Delinq_2yrs          | Integer                  | Number of delinquencies       |
| Total Payment        | Integer                  | Total payment received        |
| Received Principal   | Integer                  | Principal amount received     |
| Interest Received    | Integer                  | Interest amount received      |
| Number of loans      | Integer                  | Number of loans taken          |
| Defaulter            | Categorical              | Loan defaulter classification |

