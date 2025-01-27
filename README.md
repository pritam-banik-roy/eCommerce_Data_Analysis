# eCommerce Transactions Dataset - Data Science Assignment

This repository contains the analysis and solutions for the eCommerce Transactions Dataset assignment. The project includes exploratory data analysis (EDA), predictive modeling, and customer segmentation.

---

## Table of Contents
- [Overview](#overview)
- [Dataset Description](#dataset-description)
- [Tasks](#tasks)
  - [Task 1: Exploratory Data Analysis (EDA)](#task-1-exploratory-data-analysis-eda)
  - [Task 2: Lookalike Model](#task-2-lookalike-model)
  - [Task 3: Customer Segmentation (Clustering)](#task-3-customer-segmentation-clustering)
- [Setup and Usage](#setup-and-usage)
- [Results and Insights](#results-and-insights)
- [Technologies Used](#technologies-used)

---

## Overview
This project leverages customer and transaction data to derive insights, build predictive models, and group customers into meaningful clusters. It aims to assist businesses in improving their marketing strategies and enhancing customer engagement.

---

## Dataset Description
The dataset includes three CSV files:  

1. **Customers.csv**  
   - `CustomerID`: Unique identifier for each customer.  
   - `CustomerName`: Name of the customer.  
   - `Region`: Customer's continent.  
   - `SignupDate`: Customer signup date.  

2. **Products.csv**  
   - `ProductID`: Unique product identifier.  
   - `ProductName`: Name of the product.  
   - `Category`: Product category.  
   - `Price`: Product price in USD.  

3. **Transactions.csv**  
   - `TransactionID`: Unique transaction identifier.  
   - `CustomerID`: ID of the customer.  
   - `ProductID`: Product ID involved in the transaction.  
   - `TransactionDate`: Date of the transaction.  
   - `Quantity`: Quantity of the product purchased.  
   - `TotalValue`: Total transaction value.  
   - `Price`: Price of the product sold.  

---

## Tasks

### Task 1: Exploratory Data Analysis (EDA)
- Conducted EDA to analyze customer behavior and transaction patterns.  
- Key business insights include:
  1. Identification of high-spending regions.  
  2. Popular product categories.  
  3. Seasonal trends in transaction activity.  
  4. Customer acquisition patterns based on signup dates.  
  5. Correlation between total spending and transaction frequency.

#### Deliverables:
- `FirstName_LastName_EDA.ipynb` (Code for EDA)
- `FirstName_LastName_EDA.pdf` (Report of insights)

---

### Task 2: Lookalike Model
Developed a lookalike model to find similar customers based on profile and transaction history.  
- Used features like region, transaction behavior, and spending patterns.  
- Generated similarity scores and recommended the top 3 similar customers for each customer.

#### Deliverables:
- `FirstName_LastName_Lookalike.ipynb` (Model development code)  
- `FirstName_LastName_Lookalike.csv` (Top 3 lookalike customers with scores)  

---

### Task 3: Customer Segmentation (Clustering)
Performed customer segmentation using clustering techniques to group customers with similar behaviors.  
- Used the KMeans clustering algorithm.  
- Evaluated clusters using the Davies-Bouldin Index (DB Index) and Silhouette Score.  

#### Results:
- **Number of Clusters**: 4  
- **Davies-Bouldin Index**: 0.865 (indicating good separation and compactness).  
- **Silhouette Score**: 0.374  

#### Deliverables:
- `FirstName_LastName_Clustering.ipynb` (Clustering code)  
- `FirstName_LastName_Clustering.pdf` (Clustering report with metrics)

---

## Setup and Usage

1. Clone the repository:
   ```bash
   git clone <repository_url>
Navigate to the project directory:
bash
Copy
Edit
cd ecommerce-dataset-analysis
Install the required Python libraries:
bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter Notebooks in the following order:
FirstName_LastName_EDA.ipynb
FirstName_LastName_Lookalike.ipynb
FirstName_LastName_Clustering.ipynb
Results and Insights
EDA Insights: Provided actionable insights into customer behaviors, regional trends, and product preferences.
Lookalike Model: Identified customers with similar profiles for personalized recommendations.
Customer Segmentation: Grouped customers into clusters, helping businesses target each group effectively.
Technologies Used
Programming Language: Python
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
Tools: Jupyter Notebook
Feel free to explore the project and reach out with any questions or suggestions!

vbnet
Copy
Edit

This `README.md` template is comprehensive and adheres to best practices for documenting projects on GitHub. Let me know if you’d like any adjustments or additions!
