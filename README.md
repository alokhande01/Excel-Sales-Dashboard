# 📊 Excel Dashboard Overview

![Excel Dashboard Screenshot](Excel%20Sales%20Dashboard.png)

## 🧾 Project Summary
This project contains a **business performance dashboard** designed in Microsoft Excel to visualize key operational and sales metrics.  
The screenshot above provides a visual preview of the dashboard layout and insights.

---

## 📁 File Contents
- **dashboard_screenshot.png** — Screenshot of the Excel dashboard.
- *(Optional)* Original Excel file if available for data refresh or edits.

---

## 📈 Dashboard Insights

### 1. **Top 5 Profitable States**
Displays the states with the highest profit margins, based on total sales and profitability data.  
Example states include:
- California  
- New York  
- Ohio  
- Oregon  
- Texas  

### 2. **Top 10 Most Profitable Cities**
Highlights the top-performing cities based on profit contribution (e.g., Los Angeles, Cincinnati, Greenville).

### 3. **Top 3 Least Profitable Products**
Identifies underperforming products to guide inventory or pricing strategy.  
Example products:
- Okidata Pacemark 4410N Wide Format Dot Matrix Printer  
- Polycom ViewStation ISDN Videoconferencing Unit  

### 4. **Shipment Mode Analysis**
Breakdown of total shipments by mode:
- Delivery Truck  
- Express Air  
- Regular Air  

### 5. **Customer Segment Overview**
Distribution of sales and profits by customer segment:
- Consumer  
- Corporate  
- Home Office  
- Small Business  

### 6. **Product Category Overview**
Performance overview for:
- Furniture  
- Office Supplies  
- Technology  

---

## ⚙️ How to Use
1. Open the **Excel dashboard** to view or update the underlying data.  
2. Refresh pivot tables and charts if data changes.  
3. Re-export or update the **dashboard screenshot** after major updates.  

---

## 🧮 How to Recreate the Dashboard in Excel

### 1. **Data Setup**
Use columns:
`Order ID`, `State`, `City`, `Product`, `Category`, `Segment`, `Ship Mode`, `Sales`, `Profit`

### 2. **Pivot Tables**
| Purpose | Fields Used |
|----------|--------------|
| Top 5 Profitable States | Rows: State → Values: Sum of Profit |
| Top 10 Profitable Cities | Rows: City → Values: Sum of Profit |
| Least Profitable Products | Rows: Product → Values: Sum of Profit (sorted ascending) |
| Shipment Mode Analysis | Rows: Ship Mode → Values: Count of Orders / Sum of Sales |
| Customer Segment Breakdown | Rows: Segment → Values: Sum of Sales / Profit |
| Product Category Performance | Rows: Category → Values: Sum of Sales / Profit |

### 3. **Charts**
Create clean bar and column charts from the pivot tables.  
Use consistent color themes and remove unnecessary chart borders or legends.

### 4. **Dashboard Layout**
- Single worksheet named `Dashboard`
- 3x2 grid layout for clear organization
- Use text boxes for section titles
- Align visuals neatly and keep spacing consistent

### 5. **Interactivity**
Add **Slicers** for:
- Category  
- Segment  
- Region  

These allow quick filtering across multiple charts.

---

## 💡 Notes
- Use **landscape A4** page layout for better readability.  
- Perfect for management reviews, performance tracking, or sales analysis.  
- Use Power Query or pivot refresh for new data cycles.

---

## 🧠 Author / Maintainer
**Author:** *Abhilasha Lokhande*  
**Version:** 1.1  
**Last Updated:** October 2025  

---

## 🖼️ Output Preview
The image (`dashboard_screenshot.png`) above provides an at-a-glance view of key KPIs, top states and cities, product performance, and shipping insights.
