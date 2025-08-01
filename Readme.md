# Customer Segmentation using Machine Learning

## Project Overview

This project aims to **segment customers based on their behavior** using **unsupervised machine learning (K-Means Clustering)**. It allows businesses and marketers to better understand their customer base and **apply targeted marketing strategies**.

Dataset used: `Mall_Customers.csv`  
Source: Simulated mall customer data containing Age, Gender, Annual Income, and Spending Score.

---

## Objectives

- Segment customers into distinct groups based on purchasing behavior.
- Identify high-value customers (e.g., VIPs), bargain hunters, and less engaged shoppers.
- Enable personalized marketing, promotions, and customer relationship management.

---

## Dataset Features

| Column Name                | Description                              |
|---------------------------|------------------------------------------|
| `CustomerID`              | Unique customer identifier                |
| `Gender`                  | Gender (Male/Female)                      |
| `Age`                     | Age of the customer                       |
| `Annual Income (k$)`      | Customer’s annual income (in thousands)   |
| `Spending Score (1-100)`  | Score assigned based on spending behavior |

---

## Methodology

1. **Data Loading & Exploration**  
   - Load the dataset using Pandas and explore with `.head()`, `.info()`, and `.describe()`.
   
2. **Feature Selection**  
   - Select relevant features: `Annual Income` and `Spending Score`.

3. **Preprocessing**  
   - Apply **StandardScaler** to normalize values before clustering.

4. **Determine Optimal K**  
   - Use the **Elbow Method** to find the optimal number of clusters (K).

5. **Apply K-Means Clustering**  
   - Cluster customers into distinct segments.

6. **Visualize Segments**  
   - Create a scatter plot to visualize customer groups in 2D space.

7. **Cluster Profiling**  
   - Analyze and label each cluster based on income/spending patterns.

---

## Visualization Example

- A 2D scatter plot shows clusters using different colors.
- Example clusters:
  - **Cluster 0**: Low income, low spending
  - **Cluster 1**: High income, high spending (VIP)
  - **Cluster 2**: High income, low spending
  - **Cluster 3**: Average income, high spending

---

## Tools & Libraries Used

- Python
- Pandas
- Matplotlib & Seaborn
- Scikit-learn

---

## Potential Applications

- Personalized marketing campaigns
- Customer loyalty programs
- Cross-selling and up-selling strategies
- Customer retention and engagement analysis

---

## Results

- Identified distinct customer segments based on spending behavior and income level.
- Provided actionable insights for marketing and business strategy.

---

## Future Improvements

- Include more features (e.g., transaction history, location, online behavior)
- Use dimensionality reduction techniques like PCA for more complex datasets
- Try other clustering techniques (e.g., DBSCAN, Agglomerative Clustering)




