# 🛍 Project Title: Product Cluster Predictor

# 📌 Description:

This project is a Machine Learning Clustering Application developed using Streamlit, which helps in identifying the cluster group of a product based on its pricing details such as:

MRP (Maximum Retail Price)

Selling Price


The model uses unsupervised learning techniques (like K-Means Clustering) to group similar products into clusters. This is especially useful for:

Identifying pricing patterns

Grouping similar products for marketing or inventory planning

Detecting pricing anomalies or outliers



---

# 💡 How It Works:

The user enters the MRP and Selling Price of a product

The trained clustering model predicts the cluster number that the product belongs to

Output is displayed as:
This product belongs to Cluster X (where X is the predicted cluster label)


The clusters are formed based on the relationship between MRP and Selling Price across a dataset of products, helping categorize products into distinct price behavior groups.


---

# ✅ Key Features:

Real-time product clustering using a simple web UI

Accepts numeric inputs: MRP and Selling Price

Displays cluster prediction instantly

Useful for market segmentation, sales strategy, or discount analysis

Built using Python, Scikit-learn, and Streamlit
