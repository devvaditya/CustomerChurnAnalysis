# Databel Customer Churn Analysis
Welcome to our project presentation on reducing customer churn for subscription-based businesses. In this Power BI case study, we will explore a dataset from a sample telecom company, Databel, to analyze their churn rates. Our goal is not only to determine the churn rate but also to uncover the underlying reasons behind customer churn and develop strategies to minimize it. Through the creation of measures and calculated columns, we will provide insights and craft visually compelling report pages to answer these critical questions.

## Resources

1. Power BI Desktop - Power Query, DAX

## Project Goals

Our dashboard is designed to empower key decision-makers at Databel, including managers and stakeholders, to gain a comprehensive understanding of customer churn. It offers insightful visualizations that help analyze overall customer engagement, service usage patterns, and account activity, allowing the identification of trends and potential risk factors contributing to customer attrition.

Key objectives include:

- Identifying primary factors contributing to customer churn at Databel.
- Analyzing customer segments most at risk of leaving.
- Developing data-driven recommendations to enhance customer retention.
- Monitoring the effectiveness of retention initiatives over time.

## Data Preprocessing and CLeaning

After Loading the Data, I continued with following steps:

1. Cleaning, Formatting and Transforming Data using Power Query
2. Creating a Customer Relationship model focused on Bank Customer Churn.

## Dashboard
![image](https://github.com/devvaditya/CustomerChurnAnalysis/assets/110883375/c0758f73-079f-451d-9592-0514cf41376b)
![image](https://github.com/devvaditya/CustomerChurnAnalysis/assets/110883375/97a11357-4afc-4578-b4c1-91742142eaf1)
![image](https://github.com/devvaditya/CustomerChurnAnalysis/assets/110883375/928debd8-c3a3-4cc1-8458-dfc97f7d4f21)
![image](https://github.com/devvaditya/CustomerChurnAnalysis/assets/110883375/bdf6927a-f6d0-4ddc-ac98-56ca4df6bcfe)
![image](https://github.com/devvaditya/CustomerChurnAnalysis/assets/110883375/f36c0c2e-7b0c-4a9b-ab11-a7ec07d716a0)
## Key Insights

**1.  General Insights:**  The churn rate for Databel stands at approximately 27%, with 45% of churn attributed to competitors. Notably, the churn rate in California (CA) is significantly higher than the national average, exceeding 60%.

**2. Churn Rate by Age:** Senior citizens exhibit a churn rate 10% higher than the average, reaching 38.22%. When analyzing age groups, there is a general upward trend in churn rates as age increases.

**3. Churn Rate by Contract:** Databel offers group contracts to households, providing discounted rates and expanding its customer base. The lowest churn rate, 23%, is observed among groups of six customers. Conversely, customers on monthly contracts churn more frequently than those with yearly contracts.

**4. Churn Rate by Data Plan Usage:** Contrary to Databel's hypothesis, customers on unlimited data plans exhibit higher churn rates. Further analysis by average monthly data usage reveals that customers on unlimited plans using less than 5GB per month have the highest churn rate.

**5. Churn Rate by International Activity:** Databel is particularly interested in the impact of international activity on churn. In California, a notable 72% of churners make international calls but do not subscribe to an international plan.

**6. Churn Rate by Customer Service:** Improving customer service is a priority for Databel, as frequent customer service calls correlate with higher churn. Customers on monthly contracts who pay by direct debit make an average of 1.47 calls and have a churn rate of around 54%.

## Recommendations

- **Target International Plan Holders**:
Reach out to customers on international plans who haven't made international calls and suggest they downgrade to a cheaper plan. By offering a more cost-effective option and explaining the rationale, we aim to boost customer satisfaction and reduce churn. Additionally, the 72% of customers currently making international calls without a plan could be potential targets for a new international plan promotion.
- **Investigate Direct Debit Payment Issues**:
Given the high churn rate among customers using the direct debit payment method, it is advisable for Databel to investigate any underlying issues with this payment option. There may be problems affecting these transactions that need to be resolved to improve customer retention.
