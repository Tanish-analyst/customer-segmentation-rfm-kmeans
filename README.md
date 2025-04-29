# 🛍️ Customer Segmentation in Retail Using RFM and KMeans

This project uses real-world e-commerce data (UCI Online Retail Dataset) to segment customers based on purchasing behavior using RFM analysis and KMeans clustering. The goal is to help businesses identify VIPs, low spenders, and at-risk customers — and tailor strategies for retention, engagement, and growth.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Business Context](#business-context)
- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
- [Key Results](#key-results)
- [Business Insights](#business-insights)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Author](#author)

---

## 🔍 Overview

Customer segmentation helps businesses personalize marketing, optimize resource allocation, and boost profitability. In this project, I used RFM (Recency, Frequency, Monetary) features and applied KMeans clustering to discover meaningful customer segments.

---

## 🏢 Business Context

For e-commerce and retail businesses, not all customers hold equal value. Identifying VIPs versus one-time or disengaged customers allows companies to:

- Launch targeted campaigns
- Improve customer retention
- Boost lifetime value

---

## 📊 Dataset

- **Source**: UCI Machine Learning Repository – Online Retail  
- **Size**: ~540,000 transactions  
- **Period**: December 2010 to December 2011  
- **Fields Used**: `InvoiceNo`, `CustomerID`, `InvoiceDate`, `Quantity`, `UnitPrice`, `Country`

---

## 🔄 Project Workflow

1. **Data Cleaning & Preprocessing**
2. **Feature Engineering (RFM Variables)**
3. **Data Scaling**
4. **Optimal Cluster Selection using Elbow Method**
5. **KMeans Clustering**
6. **Segment Interpretation**
7. **Business Recommendations**

---

## 🧠 Key Results

- Identified 3 segments:
  - **VIP Customers**
  - **Low Spenders**
  - **At-Risk Customers**
- Each cluster interpreted based on RFM scores and visualized with pie/bar charts

---

## 💼 Business Insights

📌 Full business interpretations are available in the [blog post](#) (link to Medium or LinkedIn)

Highlights:

- **VIPs (19.9%)** → High spenders, great retention potential  
- **Low Spenders (68.5%)** → Frequent but low-value buyers; upsell potential  
- **At-Risk (11.5%)** → Previously active customers now disengaged  

---

## 🛠️ Technologies Used

- Python
- pandas, numpy
- seaborn, matplotlib
- scikit-learn

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/customer-segmentation-retail-rfm-kmeans.git

