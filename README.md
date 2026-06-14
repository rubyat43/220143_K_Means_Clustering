# K-Means Clustering — Customer Segmentation
**Student ID:** 220143  
**Algorithm:** K-Means Clustering  
**Dataset:** Mall Customers Dataset  

---

## Project Description
This project applies K-Means Clustering to segment mall customers based on their **Annual Income** and **Spending Score**. The optimal number of clusters was determined using the **Elbow Method**.

---

## Repository Structure

---

## Elbow Method — Finding Optimal K
The elbow curve below shows that **K=5** is the optimal number of clusters.

![Elbow Curve](elbow.png)


---

## Cluster Scatter Plot
The scatter plot below shows the 5 customer segments with centroids marked as ★

![Cluster Plot](clusters.png)


---

## Custom Data Prediction
10 real-world customers were surveyed and assigned to clusters using the trained model.

![Custom Predictions](custom.png)

---

## Cluster Interpretations

| Cluster | Profile | Description |
|---------|---------|-------------|
| 0 | High Income, Low Spender | Earn well but spend conservatively. Saving-oriented customers. |
| 1 | Low Income, Low Spender | Budget-conscious with limited purchasing power. |
| 2 | Average Customer | Middle-income moderate spenders. Most stable segment. |
| 3 |  High Income, High Spender | Wealthy customers who spend freely. Prime VIP targets. |
| 4 |  Low Income, High Spender | Impulsive buyers despite lower income. Respond to promotions. |

---

## 🔗 Links
- **Colab Notebook:** https://colab.research.google.com/drive/1NVfBFfRvCfpY5C_YwhTXGPHrZbgDGSyh?usp=sharing
- **GitHub Repo:** https://github.com/rubyat43/220143_DT_-_K_Means_Clustering
