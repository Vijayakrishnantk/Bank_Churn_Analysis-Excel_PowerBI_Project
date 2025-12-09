📊 **Bank Customer Churn Analysis – Power BI Project**

This Power BI project focuses on analyzing bank customer churn to understand why customers leave and how the bank can improve retention. It explores key churn drivers such as demographics, account features, age category, credit score and customer engagement. The insights aim to improve customer satisfaction and reduce churn rate over time. Using Excel for data preprocessing and Power BI for data visualization. The project delivers a comprehensive interactive dashboard showcasing analytical findings.



**Objectives**

1.Clean and preprocess raw dataset using Excel

2.Generate calculated fields to support analytical insights

3.Build an interactive Power BI dashboard

4.Use visualizations to understand reasons behind bank churn

5.Identify key factors influencing Customer Churn



🔍 **Key Features**

📈 Interactive Power BI dashboards for churn analysis

👥 Segmentation by age groups, gender, geography and credit score

💳 Insights into account activity, product usage and customer tenure

🎯 Identification of high-risk churn customers for targeted marketing

📉 KPI tracking: Churn Rate, Customer Distribution & Retention Metrics



🛠️ **Tools & Technologies**
| Component   | Used For                                   |
| ----------- | ------------------------------------------ |
| Excel       | Clean & Preprocess Row Data                |
| Power BI    | Data visualization & Dashboard Development |
| DAX         | Calculated Measures & Calculations         |
| GitHub      | Poject Hosting & Submission                |

**Workflow**


**Microsoft Excel - Clean & Preprocess Row Data**
  1. First arrange the data correctly.	
  2. Check data types and column name.	
  3. Review column names and changed to the Proper case format.
  4. Rename column names to Credit Score, Credit Card Status, Account Active Status, Churn Status.
  5. Check the sheet have any null data or duplicate data (No null/duplicate data found)	
  6. Modify column values for easy understanding & clarity	
	    | Column Name               | Code | Meaning     |
      | ------------------------- | ---- | ----------- |
      | Credit Card Status        | 1    | Owned       |
      |                           | 0    | Not Owned   |
      | Account Active Status     | 1    | Active      |
      |                           | 0    | Inactive    |
      | Churn Status              | 1    | Churned     |
      |                           | 0    | Not Churned |

  7. Use conditional formatting and make new columns from existing columns
     | Column Name        | Description / Derived From    |
     | ------------------ | ----------------------------- |
     | Credit Score Range | Derived from Credit Score     |
     | Age Category       | Derived from Age              |
     | Tenure Range       | Derived from Tenure           |
     | Salary Range       | Derived from Estimated Salary |
     
      | Category             | Range             | Level                     |
      | -------------------- | ----------------- | ------------------------- |
      | **Credit Score**     | ≤ 579             | Poor                      |
      |                      | 580 – 669         | Fair                      |
      |                      | 670 – 739         | Good                      |
      |                      | 740 – 799         | Very Good                 |
      |                      | ≥ 800             | Exceptional               |
      | **Age Category**     | 18 – 39           | Young Adult               |
      |                      | 40 – 59           | Middle-Aged Adult         |
      |                      | 60 – 79           | Senior Adult              |
      |                      | ≥ 80              | Oldest-Old                |
      | **Tenure**           | ≤ 1 Year          | Short-Term                |
      |                      | 1 – 5 Years       | Medium-Term               |
      |                      | > 5 Years         | Long-Term                 |
      | **Salary Range (€)** | ≤ 25,000          | Entry Level               |
      |                      | 25,000 – 50,000   | Skilled Worker            |
      |                      | 50,000 – 1,00,000 | High-Earning Professional |
      |                      | > 1,00,000        | Highly Specialized        |
      

**Microsoft Power BI - Data visualization & Dashboard Development**
 | Sl. No | Visual / Component            | Purpose / Description                                                                                              |
| ------ | ----------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| **1**  | Calculated Measures           | Create measures for: Total Bank Customers, Total Not Churned Customers, Total Churned Customers & Total Churn Rate |
| **2**  | KPI Cards                     | Display key metrics: Total Customers (10,000), Not Churned (7,963), Churned (2,037), Churn Rate (20.37%)           |
| **3**  | Donut Charts                  | Show customer proportion by Gender, Credit Card Status & Account Status                                            |
| **4**  | Tree Map                      | Visualization of customers distribution by Country                                                                 |
| **5**  | Line & Clustered Column Chart | Compare churn rate across Credit Score Range, Age Category, Tenure Range & Salary Range                            |
| **6**  | Line Chart                    | Gender-wise churned customers across different countries                                                           |
| **7**  | Clustered Column Chart        | Churned customers distribution by Number of Products                                                               |
| **8**  | Map Visualization             | Geographic view of customers by Credit Card Status                                                                 |
| **9**  | Narrative / Smart Narrative   | Auto-generated insights: Gender, Country, Products & Credit Card Status influence on churn                         |
| **10** | Table View                    | Detailed customer-level information                                                                                |
| **11** | Key Influencers               | Identifies key drivers influencing Churn behavior                                                                  |
| **12** | Slicers                       | Churn Status filter for interactive analysis                                                                       |


🔍 **Key Insights from Analysis**

🟥 Customers with low credit scores churn significantly more

🟥 Middle-Aged Adults have highr churn rate

🌍 Geographic differences strongly impact churn behavior

📌 Custtomers with shorter tenure are more likely to churn

🧾 Customers having fewer products often leave sooner

💰 High-balance churners create the highest financial loss risk

📞 Engaged customers show higher retention vs inactive users



🎯 **Conclusion**

Improving personalized communication, offering bundle benefits and targeting low-score/high-value customers can significantly reduce churn and boost long-term profitability.
