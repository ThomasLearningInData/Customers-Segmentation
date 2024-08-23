# Customers-Segmentation
I'm performing a K-Means clustering analysis on customer data, focusing on segmenting customers by Annual Income and Spending Score. Initially, I used 4 clusters, and then I tried 5 clusters. I found that using 5 clusters seemed to capture the income group between 40k to 60k more effectively, allowing for a better understanding of their unique spending behavior.

Findings:
Correlation:
![image](https://github.com/user-attachments/assets/55a6eef6-19da-47e6-90d0-8eb7bca080b2)
- Gender has a very low correlation with both "Annual Income (k$)" and "Spending Score (1-100)", indicating that gender has little influence on these variables in this dataset.

- Age has a moderate negative correlation with "Spending Score (-0.33)", meaning that as age increases, the spending score tends to decrease. This suggests older customers may have lower spending scores.

- Annual Income (k$) shows almost no correlation with "Spending Score (1-100)", indicating that income doesn't have a direct linear relationship with spending score in this dataset.

4 Clusters vs. 5 Clusters:
![image](https://github.com/user-attachments/assets/8c92abb5-824e-426c-845a-dc5bf6b4d9ce)
![image](https://github.com/user-attachments/assets/ddb325b1-9b10-4ec8-a380-46459969d814)
![image](https://github.com/user-attachments/assets/67a03bb7-e0dc-442a-961c-eda1a57442f6)
The 4-cluster model provides clear segmentation of customer groups but tends to mix the income group between 40k to 60k with other segments.
The 5-cluster model splits this middle-income group into a separate cluster, which could better represent the behavior of customers within this income range, especially regarding their spending habits.


Note: This data is fake. It is for learning purpose only.
