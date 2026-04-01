# Customer Churn Analysis (Banking)

## Project Overview
This project analyzes customer churn behavior in a retail banking dataset to identify key drivers of customer attrition and provide actionable business recommendations.

The analysis focuses on customer engagement, financial activity, and demographic factors to understand why customers leave and how banks can improve retention.

## Business Problem
Customer churn is a major challenge in the banking industry, directly impacting revenue and long-term customer value.

The goal of this project is to:
- Identify high-risk customer segments
- Understand behavioral patterns behind churn
- Provide data-driven strategies to improve retention

## Tools & Technologies
- Power BI — data visualization and dashboarding  
- DAX — calculated columns and segmentation  
- Data modeling and business analysis  

## Dataset
- Bank customer dataset (10,000 records)
- Includes:
  - Demographics (age, gender, country)
  - Financial data (balance, salary)
  - Customer behavior (products, activity)
  - Target variable: churn (0 = retained, 1 = left)

## Interactive Dashboard
[View Power BI Dashboard](https://app.powerbi.com/reportEmbed?reportId=fe0c0c8b-b76f-4448-b6e4-cccb237ee9e6&autoAuth=true&ctid=a9e39483-dd21-4c25-b848-2a625cff7939&actionBarEnabled=true)
Hover over charts to see detailed insights.

## Key Analysis

### 1. Customer Engagement (Products)
- High engagement (3+ products): **85.89% churn**
- Medium engagement (2 products): **7.58% churn (lowest)**

High engagement customers show unexpectedly high churn, suggesting dissatisfaction despite deeper product usage.

### 2. Customer Activity
- Inactive customers: **26.85% churn**
- Active customers: **14.27% churn**

Inactive users are nearly **2x more likely to churn**

### 3. Balance Segmentation
- Low balance (1–50k): **34.67% churn (highest)**
- Medium balance: **24.11%**
- High balance: **23.12%**
- No balance: **13.82% (lowest)**

Financial engagement strongly impacts retention

### 4. Age Segmentation
- Age 46–60: highest churn  
- Age 31–45: stable segment  
- Age 18–30: lowest churn  

Churn risk increases with age in this dataset

## Key Insights

### 1. Engagement is critical—but not always positive
While inactive customers churn more, extremely high engagement (3+ products) is associated with the highest churn (85.89%).

This suggests:
- possible dissatisfaction with complex product ecosystems
- poor cross-product experience
- unmet expectations among high-value users


### 2. Low-value customers are the most unstable segment
Customers with low balances (34.67% churn) are significantly more likely to leave.

This indicates:
- low switching costs
- weak relationship with the bank
- low perceived value

### 3. Activity directly impacts retention
Inactive customers are nearly twice as likely to churn.

This confirms that:
- engagement is a key retention driver  
- customers who do not interact with services are at high risk  

### 4. Age influences customer behavior
Customers aged 46–60 show the highest churn, possibly due to:
- changing financial needs  
- dissatisfaction with services  
- switching to competitors  

Younger customers (18–30) are the most stable, likely due to:
- higher digital adoption  
- early-stage financial behavior  

### 5. Financial involvement improves retention
Customers with higher balances show lower churn rates.

This suggests:
- stronger financial commitment  
- higher dependency on banking services  
- increased switching friction  

## Business Recommendations

### 1. Improve Customer Engagement
- Enhance mobile and digital experience  
- Use personalized notifications and insights  
- Encourage regular interaction  

### 2. Focus on Low-Balance Customers
- Introduce targeted offers and incentives  
- Increase perceived value (cashback, benefits)  
- Build stronger relationships early  

### 3. Investigate High-Engagement Churn (Critical)
- Analyze customer feedback  
- Simplify product ecosystem  
- Improve cross-product UX  

This segment represents a **high-value risk**

### 4. Re-Engage Inactive Customers
- Launch reactivation campaigns  
- Provide personalized offers  
- Use behavioral triggers  

### 5. Age-Based Retention Strategy
- Focus on customers aged 46–60  
- Adapt services to their financial needs  
- Improve trust and long-term value propositions  

## Conclusion
Churn is primarily driven by customer behavior rather than demographics.

Key drivers include:
- engagement level  
- financial activity  
- product usage  

Improving customer experience, simplifying products, and targeting high-risk segments can significantly reduce churn and improve long-term profitability.

---

## 👨‍💻 Author
Aspiring Data Analyst
