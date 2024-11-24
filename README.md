# Loan-Data-Analysis-with-Excel
## Project Overview
This project aims to analyze loan data to gain insights into loan performance, borrower characteristics, and repayment trends. The analysis will help in making data-driven decisions for loan approval processes and risk management.<br/>
![image](https://github.com/user-attachments/assets/2c37410b-e715-45e6-87c5-1d1c13c7f6bb)
### Data Sources - [Finance Loan dataset (1).xlsx](https://github.com/user-attachments/files/17892965/Finance.Loan.dataset.1.xlsx)
### Tool - [MSExcel](https://www.microsoft.com/en-us/microsoft-365/excel)
### Data Cleaning/Preparation<br/>
-Data Inspection<br/>
-Handling missing values<br/>
-Cleaning and formatting
### Exploratory Data Analytics (EDA)
1. What state has the most default rate?
2. What purpose do most people borrow loan for?
3. What is the ratio of the loan status?
4. Is the loan verification process effective enough?
### Data Analytics
-Pivot tables<br/>
-For the KPIs, I used 'COUNTIFS','SUM' and so on. E.g: 'COUNT(Table1[Id])' for no of loan issued.
### Results/Findings
From the analytics, I found that:
- 53% of the loan issued are for **debt consolidation**.
- Most of the loan are issued for short term.
- Approximately 14% of the total amount of issued loans are charged off.
- Those with lower annual income are borrowing higher loan amount than those with higher annual income.
- The region with the highest loan size is the **South**.
- The default rate for verified loan is higher than that of unverified loans.
- Florida has the highest default rate (17%) and Massachusetts has the least default of 11%
  ### Recommendations
  Based on my findings, I recommend that:
- The states with lower default rates may offer insights on borrower profiles that can be applied to higher-risk areas.
- It is important to manage loans for the purpose of debt consolidation carefully as it dominates the company's portfolio.
- While the charged of rate is not excessively high, it is significant enough to warant attention and further analysis should be done on it to mitigate risks.
- The company should conduct a cost-benefit analysis to determine if the effort and cost of verification are worth it, given that unverified loans have a lower default rate. They may consider revising or optimizing the verification process.
### Limitations
Some limitations in the analysis include:

- Exclusion of outlier records with extreme loan amounts or income levels to avoid skewing results.(for example, I filtered the data to include only states with a higher number of loans (e.g., a minimum threshold of loans issued) and then analyze the default rates among those states. This ensures I am drawing insights from a dataset that's large enough to be representative.
- Assumptions in handling missing values could introduce some bias.
- Data only covers a certain period and may not fully reflect current market conditions.
