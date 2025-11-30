# Customer Segmentation using RFM Analysis and Power BI Dashboard

## 📌 Project Overview
This project performs **customer segmentation** based on purchasing behavior using the **RFM (Recency–Frequency–Monetary) model**.  
The final outcome is an **interactive Power BI dashboard** that enables businesses to identify high-value customers, churn-risk customers, and segment-wise marketing opportunities.

---

## 🎯 Objective
To transform raw transaction data into actionable insights by:
- Calculating **RFM metrics** for each customer  
- Applying **K-Means clustering** for segmentation  
- Visualizing results in an **interactive Power BI dashboard**

---

## 🗂 Dataset
- **Transactions:** 80,000+ customer records  
- **Features used:** Customer ID, Invoice Date, Invoice Number, Quantity, Unit Price, Country  
- **Output table:** RFM scores + Cluster labels exported for Power BI

---

## 🔧 Tech Stack

| Component           | Tools / Libraries       |
|---------------------|-------------------------|
| Data Extraction     | SQL                    |
| ETL & Preprocessing | Python, Pandas         |
| Feature Engineering | DAX                    |
| Machine Learning    | Scikit-learn (K-Means) |
| Visualization       | Power BI               |
| Export              | CSV                    |

---

## 🛠 Workflow
1. **Data Collection** – Imported raw transactional data  
2. **Cleaning & ETL** – Removed duplicates, missing values, and invalid entries  
3. **RFM Calculation**  
   - *Recency:* Days since last purchase  
   - *Frequency:* Number of transactions  
   - *Monetary:* Total spending  
4. **RFM Scoring** – Scaled scores using quantiles  
5. **Customer Segmentation** – Applied K-Means clustering (tested 3–4 clusters)  
6. **Dashboard Development** – Created visuals to interpret segment patterns and business opportunities

---

## 📊 Dashboard Highlights
- Cluster comparison using **Box Plots**
- Segment revenue distribution using **Marimekko chart**
- **Slicers** for interactive filtering
- **Choropleth Map** to identify regions with low-recency customers
- **KPIs** showing segment-wise performance trends

---

## 📁 Repository Structure
