# OTT-Data-Analysis
An end to end customer churn analytics project focused on connecting customer behavior, subscription plans, contract types, and support interactions to identify high risk customers, revenue leakage, CLTV loss, and actionable retention opportunities.
## Business Context

The project analyzes customer, subscription, and support data from an OTT subscription platform to understand how customer behavior translates into subscription outcomes and revenue impact.

The core business problem is:

> OTT platforms need to understand why customers leave, which customer segments are most at risk, and where retention efforts can have the greatest business impact.

The analysis connects customer demographics, subscription details, contract types, churn scores, customer support activity, and CLTV to identify:

- Customer segments with high churn and retention risk
- Subscription plans and contract types associated with different churn patterns
- Customers with high churn risk and significant lifetime value
- Geographic and time-based patterns in customer churn
- Revenue and CLTV exposure associated with customer churn
- Support complaints and escalations associated with customer behavior
- Customer segments that can be prioritized for retention initiatives

The overall goal is to connect **customer behavior with subscription and revenue outcomes** and translate the findings into a clear, data-driven action plan.

## Dataset Overview

The analysis uses three interconnected datasets linked primarily through `customerid`:

| **Dataset** | **Purpose** |
|-------------|-------------|
| **Customer** | Customer demographics and geographic information |
| **Subscription** | Subscription plans, contracts, charges, CLTV, churn scores, and cancellations |
| **Support** | Customer complaints, escalations, CSAT scores, and support interactions |

### Customer

Contains customer information such as:

- Customer ID
- Customer Name
- Country
- State
- Gender
- Date of Birth

### Subscription

Contains subscription and commercial information such as:

- Customer ID
- Subscription Start Date
- Subscription Type
- Renewal Date
- Plan Type
- Contract Type
- Cancellation Date
- Cancellation Reason
- Monthly Charges
- CLTV
- Churn Score

### Support

Contains customer-support information such as:

- Customer ID
- Complaint Date
- Escalations
- CSAT Score
- Customer Comments

## Key Analysis

- Analyzed overall customer **churn and retention rates**.
- Compared churn across **Basic, Standard, and Premium plans**.
- Compared customer behavior across **monthly and annual contracts**.
- Identified geographic differences in customer churn.
- Analyzed monthly churn trends to identify periods of elevated churn.
- Segmented customers into **Low, Medium, and High churn-risk groups**.
- Analyzed the relationship between **support complaints, escalations, and churn**.
- Quantified **revenue loss and CLTV impact** associated with churn.
- Identified high-risk customers where churn and customer value overlap.
- Translated analytical findings into **retention and business action items**.

## Key Insights

- Overall **Churn Rate: 28.6%**
- **Retention Rate: 71.4%**
- Monthly contract churn: **55.6%**
- Annual contract churn: **8.3%**
- ARPU: **₹18.8**
- Revenue loss due to churn: **~₹74**
- CLTV lost from churn: **2,047**
- Revenue loss: **18%**
- September 2024 recorded the highest churn activity in the analyzed period.
- Basic subscription customers showed the highest churn in the analyzed dataset.
- Karnataka showed elevated churn and was identified for further investigation.

## Tech Stack

**Python | SQL | SQLite | Pandas | NumPy | Matplotlib | Seaborn | Jupyter Notebook**

## Analytical Skills

**Data Cleaning | SQL Queries | Joins | Aggregations | Feature Engineering | Customer Segmentation | Churn Analysis | Revenue Analysis | CLTV Analysis | Data Visualization | Business Insights**
