# **Amazon Chargeback Dashboard** 📊  

🔗 **Live Dashboard:** [Google Looker Studio](https://lookerstudio.google.com/s/ske7dRqPsI4)  

## **Project Overview**  
This dashboard was developed for **Amazon’s Chargebacks Department** to help **reduce chargebacks for authenticated transactions by 5%**. The dataset used for this project was randomly generated using Python.  

---

## **The Challenge**  

### **Objective**  
Create a **Looker Studio dashboard** for a chargeback team based on the provided dataset.  

### **How It Was Done**  

#### **1. Define 3 KPIs (Key Performance Indicators)**  
- Select at least **three relevant KPIs** to monitor chargeback performance.  
- Add them to the Looker Studio dashboard with total value visualizations.  

#### **2. Select Segmentations (Add 3 Control Filters)**  
- Identify the necessary filters that allow dashboard users to **analyze chargeback data effectively**.  

#### **3. Create Visualizations**  
- Choose at least **three different types of visualizations** to present the KPIs and enable effective data analysis.  
- Example visualization types: **bar charts, line charts, pivot tables, pie charts.**  

#### **4. Connect to the Customer Table (Optional)**  
- Optionally, **connect the dashboard to the `client_data` table** if required for KPIs or visualizations.  

---

## **Key Performance Indicators (KPIs)**  
The dashboard focuses on the following **KPIs** to analyze and optimize chargeback management:  

- **Total Chargebacks** 📈 – Represents the total number of chargebacks received, providing a general overview of the issue.  
- **Ratio of Authenticated Transactions** ✅ – Shows the percentage of transactions that were authenticated, directly tied to the department's reduction goal.  
- **Total Chargeback Amount (€)** 💰 – Displays the cumulative financial impact of chargebacks on authenticated transactions.  
- **Average Chargeback Amount (€)** 💳 – Highlights the typical monetary value of individual chargebacks.  
- **% Chargebacks Due to Missing Products** 📦 – Tracks the percentage of chargebacks caused by missing products, a key area Amazon can control to reduce losses.  

---

## **Data Visualizations**  
The dashboard includes various **visualizations** to enhance data interpretation:  

✔ **3 Pie Charts** – Chargeback status, reasons, and chargebacks with discounts.  
✔ **1 Stacked Bar Chart** – Chargeback reasons per client type.  
✔ **2 Time Series Charts** – Monthly trends of total chargebacks and average transaction values.  
✔ **Geographical Heatmaps & Demographics** – Chargebacks by country and age range.  

---

## **Data Segmentation & Filters**  
Users can **filter** the data using:  

🎯 **Country**  
🎯 **Payment Type**  
🎯 **Customer Type**  
🎯 **Chargeback Status**  

Since the dataset covers only one year, a date segmentation has not been included. However, **this could be a valuable future enhancement** if historical data is available.  

---

## **Interact with the Dashboard**  
🔍 Explore the data and discover insights by interacting with the **[Google Looker Studio Dashboard](https://lookerstudio.google.com/s/ske7dRqPsI4)**.  

Here's a preview of the dashboard in case you don't need to interact with it:

![Dashboard](Captura_Dashboard.jpg)

