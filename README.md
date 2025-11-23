# Restaurant-Sales-Analysis-Project
This project analyzes restaurant sales transactions using Excel, covering price, quantity, payment method, purchase type, city, and manager performance. Outliers were identified and removed to ensure data accuracy. An interactive dashboard with slicers and charts provides valuable insights into sales distribution, and overall business performance.

## 📌 Overview
This project is based on open-source data for educational purposes. It represents a complete sales analysis for a restaurant in Egypt, focusing on 262 transactions. Although the dataset is relatively small in size, it allowed us to extract a wide range of insights, tables, and visualizations. The dataset includes order details such as product, price, quantity, purchase type, payment method, city, and manager. Data cleaning was performed to detect and remove outliers, ensuring accurate results. An interactive Excel dashboard with slicers and charts provides clear insights into sales performance, trends, and managerial impact across different branches.

## 📊 Project Details

**Tools Used:**
- Microsoft Excel  

**Dataset:**
- Sales data including:  
  `Order ID, Date, Day, Product, Correct Price, Price, Quantity, Revenue, Purchase Type, Payment Method, Manager, City`  

**Techniques Applied:**
- Data cleaning & formatting  
- Pivot tables & charts  
- Conditional formatting  
- Data modeling  
- Dashboard design  


## 📈 Key Insights

- **Data Size:** Although the dataset contained only 262 transactions, it provided rich insights into sales behavior and management performance.  
- **Outliers:** Detected and removed unrealistic price entries that significantly affected the mean, standard deviation, and overall distribution.  
- **Manager Performance:** Sales distribution showed varying performance across managers and branches, highlighting where management impacted revenue positively or negatively.  
- **Dashboard Features:** Interactive slicers for **Payment Method, Manager, City, Product** and visualizations (bar charts, pie charts, outlier analysis).  

## 🎯 Objectives

- To analyze restaurant sales transactions and extract meaningful insights.  
- To identify and remove data outliers for more accurate results.  
- To evaluate managers’ impact on sales across different branches and cities.  
- To understand customer behavior by purchase type and payment method.  
- To design an interactive Excel dashboard with slicers and charts for better decision-making.  
- To demonstrate how even a small dataset (262 rows) can generate valuable business insights.  


## 📑 Pivot Tables Preview

--------------------------------------
| Sum of Revenue | 821,544.37 |
|----------------|------------|
--------------------------------------
| Payment Method | Percentage |
|----------------|------------|
| Gift Card      | 20.55%     |
| Cash           | 29.15%     |
| Credit Card    | 50.30%     |
| Grand Total    | 100.00%    |
--------------------------------------
| Purchase Type | Sum of Revenue |
|---------------|----------------|
| Drive-thru    | 184,259.89     |
| In-store      | 331,637.70     |
| Online        | 305,646.78     |
| Grand Total   | 821,544.37     |
--------------------------------------
| Products            | Sum of Quantity |
|---------------------|-----------------|
| Sides & Other       | 10,251          |
| Chicken Sandwiches  | 11,184          |
| Burgers             | 29,572          |
| Fries               | 33,272          |
| Beverages           | 37,090          |
| Grand Total         | 121,369         |
--------------------------------------
| City          | Sum of Revenue |
|---------------|----------------|
| Alexandria    | 211,522.88     |
| Giza          | 283,555.36     |
| Mansoura      | 143,836.02     |
| Marsa Matrouh | 81,931.16      |
| Sharm         | 100,698.95     |
| Grand Total   | 821,544.37     |
--------------------------------------
| Days       | Count of Quantity |
|------------|-------------------|
| Monday     | 31                |
| Sunday     | 35                |
| Saturday   | 35                |
| Tuesday    | 39                |
| Wednesday  | 40                |
| Thursday   | 40                |
| Friday     | 42                |
| Grand Total| 262               |
--------------------------------------
| Days       | Sum of Revenue |
|------------|----------------|
| Sunday     | 101,757.94     |
| Saturday   | 101,935.72     |
| Wednesday  | 116,762.26     |
| Thursday   | 117,979.55     |
| Friday     | 123,765.17     |
| Tuesday    | 126,879.92     |
| Monday     | 132,463.81     |
| Grand Total| 821,544.37     |
--------------------------------------
| Products      | Mohamed Hafez | Ahmed Hafez | Sara Ebrahim | Khaled Maaz | Ali Sayed | Grand Total |
|--------------------|---------------|-------------|--------------|-------------|-----------|-------------|
| Beverages          | 52,329.96     | 31,004.50   | 14,000.70    | 22,402.30   | 10,201.10 | 129,938.56  |
| Burgers            | 121,574.46    | 93,268.20   | 70,639.62    | 60,676.29   | 45,841.71 | 392,000.28  |
| Chicken Sandwiches | 35,996.70     | 30,148.50   | 20,855.20    | 16,079.20   | 12,059.40 | 115,139.00  |
| Fries              | 47,716.88     | 34,638.25   | 15,415.33    | 19,620.78   | 12,616.35 | 130,007.59  |
| Sides & Other      | 18,351.30     | 15,044.85   | 8,023.92     | 9,026.91    | 4,011.96  | 54,458.94   |
| **Grand Total**    | 275,969.30    | 204,104.30  | 128,934.77   | 127,805.48  | 84,730.52 | 821,544.37  |
--------------------------------------
| Managers       | Alexandria | Giza       | Mansoura   | Marsa Matrouh | Sharm       | Grand Total |
|----------------|------------|------------|------------|---------------|-------------|-------------|
| Ahmed Hafez    | 171,259.32 |            | 18,823.04  | 14,021.94     |             | 204,104.30  |
| Ali Sayed      | 13,619.25  | 18,028.97  |            | 53,082.30     |             | 84,730.52   |
| Khaled Maaz    |            | 8,804.11   | 108,776.27 | 10,225.10     |             | 127,805.48  |
| Mohamed Hafez  | 26,644.31  | 228,486.46 | 16,236.71  | 4,601.82      |             | 275,969.30  |
| Sara Ebrahim   |            | 28,235.82  |            |               | 100,698.95  | 128,934.77  |
| **Grand Total**| 211,522.88 | 283,555.36 | 143,836.02 | 81,931.16     | 100,698.95  | 821,544.37  |
--------------------------------------
| Month | Sum of Revenue |
|------------|----------------|
| **November** |                |
| 07-Nov     | 5,206.95       |
| 08-Nov     | 14,423.71      |
| 09-Nov     | 14,225.70      |
| 10-Nov     | 15,222.81      |
| 11-Nov     | 14,424.63      |
| 12-Nov     | 14,021.94      |
| 13-Nov     | 54,548.00      |
| 14-Nov     | 32,546.90      |
| 15-Nov     | 13,628.16      |
| 16-Nov     | 13,628.16      |
| 17-Nov     | 14,021.94      |
| 18-Nov     | 14,415.72      |
| 19-Nov     | 14,026.02      |
| 20-Nov     | 8,219.12       |
| 21-Nov     | 14,018.78      |
| 22-Nov     | 13,616.09      |
| 23-Nov     | 13,823.93      |
| 24-Nov     | 19,030.88      |
| 25-Nov     | 13,417.16      |
| 26-Nov     | 13,222.31      |
| 27-Nov     | 13,417.16      |
| 28-Nov     | 13,424.40      |
| 29-Nov     | 13,424.40      |
| 30-Nov     | 13,619.25      |
| **December** |                |
| 01-Dec     | 13,420.32      |
| 02-Dec     | 14,021.94      |
| 03-Dec     | 14,021.94      |
| 04-Dec     | 9,011.51       |
| 05-Dec     | 14,225.70      |
| 06-Dec     | 14,017.86      |
| 07-Dec     | 14,021.94      |
| 08-Dec     | 14,216.79      |
| 09-Dec     | 14,619.48      |
| 10-Dec     | 14,619.48      |
| 11-Dec     | 15,027.92      |
| 12-Dec     | 14,619.48      |
| 13-Dec     | 14,619.48      |
| 14-Dec     | 14,623.63      |
| 15-Dec     | 14,415.79      |
| 16-Dec     | 15,019.08      |
| 17-Dec     | 15,425.85      |
| 18-Dec     | 15,620.70      |
| 19-Dec     | 15,824.46      |
| 20-Dec     | 16,019.31      |
| 21-Dec     | 16,422.00      |
| 22-Dec     | 16,621.00      |
| 23-Dec     | 16,017.71      |
| 24-Dec     | 16,420.40      |
| 25-Dec     | 16,619.40      |
| 26-Dec     | 17,013.25      |
| 27-Dec     | 17,013.25      |
| 28-Dec     | 17,614.94      |
| 29-Dec     | 16,815.64      |
| **Grand Total** | 821,544.37 |
--------------------------------------





## 📈 Dashboard Preview
<img width="699" height="387" alt="Dashboard" src="https://github.com/user-attachments/assets/4fecf38d-9b02-4893-8ac4-3cfc99f5d280" />



## 📊 Statistics Preview
<img width="839" height="368" alt="Statistics" src="https://github.com/user-attachments/assets/66faaa5b-62bd-4a10-9d15-21c251bdc497" />







## ⚠️ Outliers Preview
<img width="898" height="461" alt="Outliers" src="https://github.com/user-attachments/assets/aec5f569-8765-4e86-a707-f80bfeb8e4c5" />








## 📝 Notes & Observations

- **Lowest orders but highest revenue:**  
  One specific day recorded the fewest transactions but generated the highest revenue, indicating larger purchase sizes or higher-value products sold.  

- **Outliers linked to one manager:**  
  All price outliers were traced back to a single manager in one branch, selling multiple products **in-store using credit card payments**. This suggests possible data entry errors or a recurring issue with the payment system.  

- **Revenue peaks:**  
  - Highest revenue day: **13 November**  
  - Lowest revenue day: **7 November**  

- **Correct Price validation column:**  
  A new column *Correct Price* was created using the following formula to automatically flag potential outliers:  
  ```excel
  =IF(OR([@Price]>AVERAGE([Price])+3*STDEV([Price]),
         [@Price]<AVERAGE([Price])-3*STDEV([Price])),
     "Outlier","OK")
"This method allowed quick detection of invalid entries and ensured more reliable analysis."


## 💡 Recommendations:

Monitor sales trends regularly to identify peak and low-performing days.

Investigate unusual transactions to ensure data accuracy and prevent errors.

Encourage managers to review branch-specific performance and apply best practices.

Optimize product pricing and promotions based on demand patterns.

Expand analysis with larger datasets or advanced BI tools for deeper insights.




## 🗂 Files in This Repository

Original Folder → The main Excel file containing data before cleaning ( Original Data.xlsx )


The Excel file containing Data Analysis Results ( Restaurant Sales Analysis Project 3.xlsx )



