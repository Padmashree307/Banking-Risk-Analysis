# Risk Analysis in Banking: End-to-End Data Analytics Project

##  Project Overview

This project focuses on developing a comprehensive understanding of **risk analytics in the banking and financial services sector**, with an emphasis on how data can be leveraged to **minimize financial loss while lending to customers**. Through a structured data analytics pipeline, from raw data to actionable insights, this project demonstrates the practical application of data science and business intelligence in mitigating credit risk.

---

##  Problem Statement

Develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimize the risk of losing money while lending to customers.

---

##  Project Workflow

1. **Dataset Acquisition**
   - A structured dataset with **3000 rows and 25 columns** representing customer profiles, financial transactions, and banking behavior.
   
2. **Data Integration**
   - Dataset imported into **Jupyter Notebook** via **MySQL** connectivity.
   
3. **Data Cleaning & Preprocessing**
   - Handled missing values, created new derived features like `Engagement Timeframe`, `Engagement Days`, and `Income Band`.
   - Formatted and standardized key attributes for downstream analysis.

4. **Exploratory Data Analysis (EDA)**
   - Identified patterns and trends using Python (Pandas, Matplotlib, Seaborn).
   - Generated customer-level and portfolio-level insights to support risk profiling.

5. **Database Upload**
   - Processed data pushed back to **MySQL** for structured querying and BI connectivity.

6. **Business Intelligence & Visualization**
   - Data imported into **Power BI**.
   - Built interactive dashboards to present:
     - Loan, deposit, and client distribution
     - Risk categorization and key KPIs
     - Detailed visuals across account types and bank segments

---

##  Insights

### 1. Private Banks Have a Higher Client Base  
Analysis revealed that private banks have a significantly higher number of clients compared to public or international banks.  
**Significance**: Indicates greater exposure to customer risk in the private sector. Risk mitigation strategies and compliance monitoring may need to be more rigorous for these institutions.


### 2. High Loan Amounts Are Concentrated Among Specific Demographics  
Segmentation of loan amounts by nationality and gender showed that certain demographic groups are associated with higher credit exposure.  
**Significance**: Enables targeted credit risk assessment and informs policy decisions around lending thresholds or scoring models for specific groups.


### 3. Client Engagement Duration Affects Financial Behavior  
A derived metric (`Engagement Days`) indicated that long-term clients generally have more consistent financial patterns across deposits and loans.  
**Significance**: Helps in identifying trusted, low-risk clients versus new or short-term clients who may need stricter monitoring.


### 4. Clients with Low-to-Mid Incomes Form the Majority  
Income bands were created using binning techniques, and it was observed that most clients fall under low to mid income categories.  
**Significance**: Assists in designing inclusive, income-sensitive financial products while also applying risk buffers for lower-income segments.


### 5. Processing Fees Are a Notable Source of Revenue  
By calculating estimated processing fees using DAX and applying them across loan products, it was found that they contribute significantly to bank revenue.  
**Significance**: Understanding this revenue stream can help in designing fee structures and determining the impact of waivers or discounts on profitability.

---

##  Power BI Dashboard Features

- **KPI Scorecards**: Total Clients, Total Loan, Total Deposit, Total Fees
- **Loan Analysis**: Visual breakdown by loan types and investor categories
- **Deposit Analysis**: Account-wise deposit patterns and volume
- **Client Behavior**: Engagement days, fee structures, and processing fees
- **Segmented Risk Analysis**: Credit card balances, savings vs checking behavior, and foreign currency metrics

> Built using custom DAX measures and calculated columns (e.g., `SUMX`, `SWITCH`, `DATEDIFF`) for dynamic visualizations.

---

##  Repository Structure

```
Risk-Analysis-Banking
├── Banking.xlsx            # Raw dataset
├── Banking Project.ipynb   # Jupyter Notebook for data cleaning, EDA
├── Banking Dashboard.pbix  # Power BI dashboard file
└── README.md               # Project documentation

```
---

##  Conclusion

This project demonstrates how **data-driven decision making** using analytical methods and BI tools can significantly enhance **risk assessment** in banking. The final Power BI dashboard delivers clear, interactive insights for understanding loan exposure, deposit behavior, and client segmentation.

---

##  Real-World Relevance

This project showcases how data analytics and business intelligence can be applied in the financial sector to improve decision-making, reduce lending risk, and better understand customer behavior. The workflow and dashboard design are aligned with industry practices used by modern banks and fintech institutions.

---

##  Future Scope

- Extend the project with **predictive modeling** to forecast default risk.
- Integrate **real-time data** for live dashboarding and alerts.
- Perform **customer segmentation** using clustering or classification models.
- Enhance dashboard with drill-down reports for branch-level insights.

---

##  Technologies Used

- **Programming**: Python
- **Database**: MySQL
- **Visualization**: Power BI
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn
- **Tools**: Excel, DAX, SQL

---

##  Author

**I Padmashree**  
**Email:** [iipadmashreeee@gmail.com](mailto:iipadmashreeee@gmail.com)  
**LinkedIn:** [www.linkedin.com/in/padmashree02](https://www.linkedin.com/in/padmashree02)

---

##  License

This project is intended for educational and portfolio use only.


