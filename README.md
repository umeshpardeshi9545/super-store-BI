# Superstore Sales Dashboard

This repository contains an interactive **Superstore Sales & Orders Dashboard** built using Excel.  
It is designed to help business users quickly explore sales performance, customer behavior, and order-level details for a fictional superstore dataset.

---

## 📊 Dashboard Overview

The solution consists of **two main views**:

1. **Sales Overview (Page 1)**  
   - High-level KPIs:
     - **Total Sales:** 1,990.79K  
     - **Total Profit:** 346.33K  
     - **Total Orders:** 7,943  
     - **Sub-Categories Covered:** 17  
   - **Time Series**: Total Sales & Total Profit by Year, Quarter, and Month.  
   - **Profit by Segment**: Donut chart highlighting contribution of Corporate, Consumer, and Home Office segments.  
   - **Orders by Region**: Pie chart showing order share from West, East, Central, and South regions.  
   - **Top Cities by Orders**: Bar chart with top-performing cities like New York City, Los Angeles, San Francisco, etc.  
   - **Order Detail Table**: Scrollable table listing:
     - Order ID  
     - Product Name  
     - (and other related fields, depending on the file)

2. **Order Details (Page 2)**  
   - Drill-down view for any specific order.  
   - Displays:
     - **Order ID**  
     - **Customer ID & Customer Name**  
     - **Product ID & Product Name**  
     - **Country, Region, City**  
     - **Quantity**  
     - **Sales Amount**  
     - **Return Status** (Yes/No indicator)  
   - Useful for quickly checking the full context of an individual order.

---

## 🎛 Filters & Interactivity

Both pages are fully interactive using slicers:

- **Category**
- **Sub-Category**
- **Country**
- **Region**
- **City**
- **Segment**
- **Order Date Range (2019-02-01 to 2020-12-30)**  

There is also an **“Apply all slicers”** button to update all visuals based on the selected filters, making the analysis fast and user-friendly.

---

## 🛠 Tech Stack

- **Tool:** Microsoft Excel (Dashboard + Slicers + Pivot Tables/Charts)  
- **Data Source:** Superstore sales dataset (Orders & Returns data)  
- **Visual Elements:**  
  - Pivot Charts (Line, Pie, Donut, Bar)  
  - Card KPIs  
  - Slicers for all key dimensions  

---

## 🔍 Key Business Questions Answered

- What are the **overall sales, profit, and order volume** during the selected period?
- Which **regions and segments** are the most profitable?
- Which **cities generate the highest number of orders**?
- How do **sales and profits trend over time** (year/quarter/month)?
- What are the full **details for a specific order**, including customer, product, quantity, and whether it was returned?

---

## 📁 Repository Structure

```text
.
├── data/
│   └── superstore_sales_data.xlsx      # Raw / cleaned dataset (if shared)
├── dashboard/
│   └── Superstore_Sales_Dashboard.xlsx # Final interactive Excel dashboard
├── images/
│   ├── sales_dashboard.png             # Sales overview screenshot
│   └── order_details_dashboard.png     # Order details screenshot
└── README.md
