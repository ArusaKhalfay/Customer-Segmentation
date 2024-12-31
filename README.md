# Customer Segmentation for an Online Retail Business  

## Project Motivation  
Understanding customer behavior is crucial for developing targeted marketing strategies and optimizing resource allocation. This project segments customers based on their purchasing habits to create actionable insights. By identifying distinct customer clusters, businesses can personalize their approach to nurturing, retaining, and engaging customers, ultimately enhancing customer satisfaction and boosting revenue.  

---

## Exploratory Data Analysis (EDA)  
To gain meaningful insights, the following EDA steps were performed:  

1. **Data Cleaning**:  
   - Removed duplicates and handled missing values.  
   - Addressed outliers in key variables such as monetary value and frequency of purchases.  

2. **Feature Engineering**:  
   - Calculated **Recency**, **Frequency**, and **Monetary Value (RFM)** for each customer.  
   - Normalized features to ensure fair comparison during clustering.  

3. **Visualization**:  
   - Used histograms, box plots, and scatter plots to examine variable distributions and relationships.  
   - Visualized customer behavior trends to uncover preliminary patterns.  

---

## Cluster Analysis  
1. **Clustering Approach**:  
   - Applied **K-Means Clustering** to group customers based on RFM features.  
   - Determined the optimal number of clusters using the **Elbow Method** and **Silhouette Score**.  

2. **Cluster Validation**:  
   - Evaluated cluster stability and interpretability.  
   - Analyzed within-cluster sum of squares (WCSS) for optimal performance.  

---

## Findings and Insights 
![output](https://github.com/user-attachments/assets/863a893b-3870-45b4-80f0-c49de341a44c)

- **Cluster 1**: High Recency, Low Frequency, and Low Monetary Value (Inactive or Low-Value Customers).  
- **Cluster 2**: Moderate Recency, High Frequency, and High Monetary Value (Loyal Customers).  
- **Cluster 3**: Low Recency, Low Frequency, and High Monetary Value (Potentially High-Value Dormant Customers).  
- **Cluster 4**: High Recency, High Frequency, and Moderate Monetary Value (Frequent Shoppers).  

Each cluster represents distinct customer personas that can be targeted for tailored marketing strategies.  

---  
