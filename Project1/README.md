# Project 1: Customer Purchase Behaviour Analysis

This project involves exploratory data analysis (EDA) on two datasets, merging them to uncover valuable insights. The analysis demonstrates data wrangling, cleaning, and visualization techniques.

---

## **Datasets Used**

### **1. Customer Data**
- **Description:** Contains information about customers, such as demographics and purchasing behavior.
- **Key Columns:**
  - `LYLTY_CARD_NBR`: Unique identifier for each customer.
  - `LifeStage`: Customer's stage in life (e.g., Youth, Midage, Retired).
  - `Premium Customer`: Indicates the customer segment range like Budget, Premium, Mainstream .

### **2. Transactions Data**
- **Description:** Contains transactional details for purchases made at different stores.
- **Key Columns:**
  - `LYLTY_CARD_NBR`: Unique identifier for each customer transaction.
  - `TOT_SALES`: Total sales amount for the transaction.
  - `PROD_NAME`: Name of the purchased product.
  - `PackSize`: Packaging size of the product (e.g., 500g, 1L). Extracted Column
  - `Brand`: Brand of the product. Extracted Column
  - `STORE_NBR`: Identifier linking the store to customer data.

---

## **Project Flow**

### **1. Data Import and Cleaning**
- Imported the two datasets into a Python environment using `pandas`.
- Performed basic cleaning:
  - Removed duplicates and null values.
  - Standardized column names for consistency.
  - Ensured data types were appropriate for analysis.


### **2. Exploratory Data Analysis (EDA) on both data set individually**
- Conducted descriptive analysis to understand key statistics of the data.
- Performed GroupBy Operation for meaningful Insights.
- Created visualizations using library such as `plotly`

### **3.Merging both dataset on common column LYLTY_CARD_NBR **

### **4. Insights and Observations**
- Identified patterns in customer behavior across different life stages and premium membership groups.
- Analyzed which brands and products were most popular based on sales.
- Determined high-performing packsize.

---

## **Tools and Libraries Used**
- **Programming Language:** Python
- **Libraries:** 
  - `pandas` for data manipulation.
  - `plotly` for data visualization.

---

## **Project Files**
- `CustomerPurchaseBehaviourAnalysis.ipynb`: Contains the complete Python code for the analysis.
- `QVI_purchase_behaviour.csv`: Customer data file.
- `QVI_transaction_data.xlsx`: Transactions data file.
