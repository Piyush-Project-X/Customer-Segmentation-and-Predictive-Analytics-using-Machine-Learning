# **Customer Segmentation and Predictive Analytics using Machine Learning**

A comprehensive project designed to leverage **K-Means Clustering** for customer segmentation and **Logistic Regression** for predictive analytics. This initiative focuses on analyzing customer transactional data to uncover trends, classify customers into meaningful segments, and enhance business strategies through data-driven insights.

---

## **Table of Contents**

- [Project Overview](#project-overview)
- [Data Description](#data-description)
- [Implementation Details](#implementation-details)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [Results and Insights](#results-and-insights)
- [How to Run the Project](#how-to-run-the-project)
- [Future Improvements](#future-improvements)

---

## **Project Overview**

A comprehensive approach to customer segmentation and classification, combining **unsupervised learning** with **predictive modeling**. This project enables businesses to identify customer groups, predict customer segments, and enhance decision-making processes for targeted marketing and personalized customer experiences.

---

## **Data Description**

The dataset includes anonymized customer transaction records and consists of the following features:

- **Frequency:** Number of transactions by a customer.
- **Monetary Value:** Total spending by a customer (normalized).
- **Recency:** Number of days since the customer's last transaction.

---

## **Implementation Details**

### **1. Data Preprocessing:**
- Cleaned the dataset and handled missing values.
- Standardized features for consistent scaling.

### **2. Customer Segmentation:**
- Applied **K-Means Clustering** to segment customers into distinct groups.
- Validated clusters using the **Davies-Bouldin Index**.
- Reduced dimensionality using **Principal Component Analysis (PCA)** for 2D/3D visualization.

### **3. Predictive Modeling:**
- Used **Logistic Regression** to classify customers into the identified segments.
- Evaluated the model with metrics like **accuracy**, **precision**, **recall**, and **F1-score**.

### **4. Visualization:**
- Generated scatter plots and cluster visualizations using **Matplotlib** and **Seaborn**.

---

## **Key Features**

- **Actionable Segments:** Segmented customers into clusters for better understanding and strategy formulation.
- **Predictive Framework:** Developed a supervised model to predict customer clusters accurately.
- **Interactive Visualizations:** Created intuitive visual representations to aid in business insights.
- **Scalable Workflow:** Designed a robust pipeline adaptable for larger datasets and additional algorithms.

---

## **Technologies Used**

- **Languages:** Python
- **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
- **Techniques:** K-Means Clustering, Logistic Regression, PCA, Feature Scaling, Model Evaluation

---

## **Results and Insights**

- **Customer Profiles:** Identified three distinct customer groups:
  - **Cluster 0:** High-frequency buyers with moderate spending.
  - **Cluster 1:** Low-frequency but high-value buyers.
  - **Cluster 2:** Infrequent, low-value customers.
- **Model Accuracy:** Achieved high performance in cluster prediction, ensuring reliable insights.
- **Business Value:** Facilitated personalized marketing strategies and improved resource allocation.

---

## **How to Run the Project**

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-segmentation-analytics.git
   cd customer-segmentation-analytics
