![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)


# Banker-Exit-Insights

# Summary
This dashboard provides insights into patterns observed when banking customers exit. It analyzes variables such as purchased products, credit score, age, account balance, and whether they are credit card holders or active members of the bank.


# Dashboard
![image](https://github.com/user-attachments/assets/9a1bb22b-bbd8-4ed2-a4d8-8d5c19e04434)

# Steps to Create the Dashboard
Step 1: Load Data into Power BI Desktop
- The dataset, "churn.xls," was loaded into Power BI Desktop for analysis.

Step 2: Open Power Query Editor and Enable Data Profiling
- In the Power Query editor, the "Column distribution," "Column quality," and "Column profile" options were enabled for an overview of data quality.

Step 3: Enable Profiling on the Entire Dataset
- Set "Column profiling based on the entire dataset" to ensure a complete data assessment.

Step 4: Check for Data Quality Issues
- Confirmed there were no errors or empty values across columns, ensuring data consistency.

Step 5: Transform Binary Columns 
- Changed the values in the 'HasCrCard,' 'Exited,' and 'IsActiveMember' columns from 1 and 0 to 'Yes' and 'No' for easier interpretation.

Step 6: Select Theme for Report View
- Choose an appropriate theme to enhance readability.

Step 7: Create Visuals Based on Storyboard

Banker Distribution by Geography
- Breakdown of customers in France, Germany, and Spain, highlighting key markets like Germany and France for focused engagement efforts.

Balance by Number of Products
- Analysis of customer balances by product ownership, segmented by exit status, revealing trends in retention and cross-selling opportunities.

Bankers with Credit Cards
- A donut chart showing credit card ownership proportions, helping assess product reach and plan strategies to boost adoption.

Balance by Age
- Scatter plot analyzing customer balances by age group to identify demographics with higher balances for targeted premium services and retention.

Active vs. Inactive Bankers
- Donut chart showing active vs. inactive customers, offering insights for re-engagement initiatives to improve retention.

Bankers by Credit Range Category
- Treemap categorizing customers by credit score (Poor to Excellent), with drill-through capabilities for detailed customer insights by credit range.

Step 8: Add Interactive Filters
- Added slicers for "Exit" and "Geography" enabling users to filter data by specific exiting or non-exiting customers in France, Germany, or Spain.
  
![filter](https://github.com/user-attachments/assets/7c997dff-0d3c-483a-8628-4505dfd5aa0d)

Step 9: Utilize Drill Through Function
- Added a drill-through feature in the treemap, allowing users to access detailed banker information such as CustomerID, Surname, Tenure, etc for deeper insights.

![image](https://github.com/user-attachments/assets/311a0563-7f7e-4d77-a1d6-edaf3c89e593)

  
Step 10: Document Visualizations and Functionality
- Screenshots of each visual were added to the accompanying analysis document, with explanations for each chart type chosen.
- Verified and documented that filter functionality works as expected.


# Insights from the Dashboard
In France, Germany, and Spain
- Bankers who purchased more products were more likely to exit.
  
![image](https://github.com/user-attachments/assets/a5a3144d-185f-4592-bd5f-2c45d0dbca96)

- Although most customers were credit card holders, exiting customers were generally not active members of the bank.
  
![image](https://github.com/user-attachments/assets/1359327c-0337-4d71-820f-2fa4a8a97d91)

- Both exiting and non-exiting customers had credit scores between 300 and 739, classified as Poor, Fair, or Good.
  
![image](https://github.com/user-attachments/assets/43d9f400-abfd-4813-9031-e0f3c25d19ea)

- The data is most dense for *exiting customers* in the age range of ~30-60 at balance ~$50K-200K

![image](https://github.com/user-attachments/assets/6ffc4bbf-81c4-4164-9857-a9410ccd6fd1)

- The data is most dense for *non-exiting customers* in the age range of ~18-60 at balance ~$50K-200K

![image](https://github.com/user-attachments/assets/ce871ee0-1ab1-4a75-8fdc-78cbcacac221)


# Bank Recommendations:
- Encourage customers to limit purchases to no more than 2 products.
- Develop strategies to promote increased engagement with customers.
