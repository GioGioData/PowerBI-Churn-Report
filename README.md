# PowerBI-Churn-Report
# Customer Churn Analysis 
## 1.1 Project Overview

This project utilizes Power BI to analyze customer churn, focusing on understanding the key factors driving attrition and identifying actionable insights to improve customer retention. By leveraging a dataset covering customer demographics, service usage, contract details, and churn reasons, the project offers data-driven strategies for reducing churn rates and fostering long-term customer loyalty.
## 2.1 Database Overview

The dataset contains rich customer information, including:

- **Account Details:** Contract type, account length, and billing data.  
- **Service Usage:** Local and international calls, data consumption, and charges.  
- **Customer Behavior:** Monthly charges, extra fees, and international plan usage.  
- **Churn Indicators:** Labels for churned and retained customers, along with specific reasons for churn.  

The dataset’s multidimensional nature enables a deep dive into customer behavior and its relationship to churn, facilitating detailed analysis across demographics, service features, and billing patterns.
## 3.1 Analysis Performed

### 3.1.1. Churn Rate and Reasons

The churn rate was calculated at **26.86%**, as shown in the top-left metric. The bar chart highlights the most common reasons for churn:

- **Competitor offers better service or pricing** dominate the list.  
- Issues like **"Attitude of support staff"** and **"Price too high"** also rank high.  

The pie chart visualizes churn categories, with competitor-related churn accounting for the majority, emphasizing the competitive nature of the market.
### 3.1.2 Contract Type and Churn Relationship

The analysis revealed that customers with **month-to-month contracts** have the highest churn rate at **51.01%**. This is evident from the donut chart, where month-to-month contracts dominate the churned customer segment. Longer-term contracts (one-year and two-year) show significantly lower churn rates, suggesting a need to encourage longer commitments.

---

### 3.1.3 Account Length and Churn

The bar and line chart illustrate the relationship between **account length** and churn rate:

- Customers with shorter account tenures (e.g., 1–6 months) exhibit the highest churn rates.  
- As account tenure increases, churn rates decline, demonstrating the importance of retaining new customers early.  

This analysis highlights the need for improved engagement during the initial months of a customer’s journey.

---

### 3.1.4 Charges and Churn Behavior

High monthly charges and extra fees are strong predictors of churn:

- The grouped bar chart shows customers without unlimited data plans have higher churn rates, especially those incurring charges for higher data or international usage.  
- Customers with less than **5GB of extra usage** have significantly lower churn rates compared to heavy users.  

Tailored pricing models or incentives for high-spending customers could address these concerns.

---

### 3.1.5 Geographical Distribution of Churn

The map visualization highlights regional disparities in churn rates. Certain states exhibit significantly higher churn, pointing to the need for region-specific strategies. For example, states with red markers indicate areas with a higher proportion of churned customers.

Understanding local market dynamics and addressing region-specific challenges can help improve retention in these high-risk areas.

---

### 3.1.6 Customer Service and Churn

A scatter plot analysis demonstrates the relationship between **customer service interactions** and churn:

- Customers who make frequent service calls tend to have higher churn rates, indicating potential dissatisfaction with issue resolution or service quality.  

This finding underscores the need to enhance customer support processes, improve first-call resolution rates, and provide proactive solutions to customer concerns.

## 3.2 Key Insights

From the analysis, the following insights were drawn:

1. **Competitor Influence Drives Churn**  
   Competitor offerings, particularly better pricing or service, are the leading reasons for churn. Businesses must remain competitive and differentiate their value propositions.

2. **Short-Term Contracts Increase Churn Risk**  
   Month-to-month contracts show significantly higher churn rates compared to longer-term commitments. Encouraging longer contracts with discounts or added benefits could improve retention.

3. **Pricing Sensitivity is High**  
   High monthly charges and additional fees are critical churn drivers. Offering tailored pricing solutions for high-value customers and unlimited plans for heavy users could mitigate this risk.

4. **New Customers are Vulnerable**  
   Churn rates are highest among customers with short account tenures, emphasizing the importance of onboarding programs and personalized engagement during the early stages.

5. **Customer Service Quality Matters**  
   Frequent service calls correlate with churn, indicating dissatisfaction. Investments in customer service training and technology could reduce churn by improving customer satisfaction.

6. **Regional Strategies are Essential**  
   Geographical differences in churn rates suggest the need for targeted retention efforts in high-risk areas, based on localized challenges and preferences.
## 4.1 Conclusion

This Power BI analysis effectively identifies key churn drivers and provides actionable insights to improve customer retention strategies. Addressing pricing concerns, enhancing service quality, and encouraging long-term contracts are critical steps to reducing churn. Additionally, region-specific strategies and early engagement programs can further strengthen customer loyalty.

The visualizations in this report offer a clear and data-driven foundation for strategic decision-making, enabling businesses to respond effectively to churn challenges and build sustainable customer relationships.
