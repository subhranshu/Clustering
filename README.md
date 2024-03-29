# Customer Segmentation Project

## Overview
This project focuses on analyzing customer behavior and segmenting them based on their purchasing patterns using RFM (Recency, Frequency, Monetary value) analysis. The goal is to gain insights into customer segments and their characteristics to help make data-driven marketing decisions.

## Problem Statement
The company wants to understand its customer base better and identify key customer segments for targeted marketing campaigns. Specifically, the project aims to answer the following questions:
- Which customer segments are the most profitable?
- How do new and existing customers contribute to revenue?
- Are there any distinct patterns in customer behavior based on recency, frequency, and monetary value?

## Dataset
The dataset used for this analysis is from an online retail store and contains information such as customer ID, invoice details, product descriptions, quantities, prices, and country.

## Project Steps
1. **Data Import and Cleaning:**
   - Imported the dataset into Pandas DataFrame.
   - Cleaned the data by handling missing values, removing duplicates, and filtering out irrelevant records.

2. **Data Exploration:**
   - Analyzed year-wise monthly revenue trends to identify patterns and anomalies.
   - Explored monthly item sales and active customer trends.
   - Examined average revenue per month and its variation over time.
   - Segmented customers into new and existing users to compare revenue contributions.

3. **Customer Segmentation using RFM Analysis:**
   - Calculated recency, frequency, and monetary value metrics for each customer.
   - Conducted K-means clustering to group customers into distinct clusters based on RFM scores.
   - Analyzed cluster characteristics and identified key customer segments.

4. **Hierarchical Clustering Experiment:**
   - Explored hierarchical clustering as an alternative approach to customer segmentation.
   - Evaluated clusters based on recency, frequency, and monetary value metrics.

5. **Visualization and Insights:**
   - Visualized clusters using scatter plots and 3D plots to showcase customer segmentation results.
   - Provided insights and interpretations on each cluster's characteristics and implications for marketing strategies.

## Results and Findings
- Identified three main customer segments: Churned customers, Top customers, and Casual customers.
- Churned customers represent a significant portion of the customer base but contribute less revenue.
- Top customers exhibit high frequency and monetary value, making them valuable for targeted campaigns.
- Casual customers make up the largest segment but have lower spending compared to other clusters.

## Recommendations
Based on the analysis, the following recommendations are suggested:
- Focus marketing efforts on retaining top customers and re-engaging churned customers.
- Offer personalized promotions and incentives to encourage repeat purchases from casual customers.
- Continuously monitor customer behavior and adjust strategies to maximize revenue and customer satisfaction.

## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Plotly

## Future Work
Future enhancements to this project could include:
- Implementing predictive modeling to forecast customer behavior and lifetime value.
- Incorporating additional customer attributes or segmentation criteria for more granular analysis.
- Deploying interactive dashboards or web applications for real-time insights and decision-making.
