# Power BI Sales Dashboard

This repository showcases a Power BI dashboard project that analyzes sales data to extract actionable insights. The dashboard leverages data transformation, dimensional modeling, and interactive visualizations to deliver a comprehensive view of sales performance, product trends, time-based insights, and shipping metrics.
Refer to the report pdf for details on the steps I took and insights I found during analysis.

---

## Features

- **Data Transformation**: Cleaned and optimized the raw sales data by handling unnecessary columns, creating lookup tables, and ensuring data integrity.
- **Dimensional Modeling**: Organized data into fact and dimension tables for efficient storage and analysis.
- **Calculated Columns and Measures**:
  - Added a `DaysToShip` column (`ShipDate - OrderDate `) for streamlined analysis.
  - Created time intelligence measures (e.g., YTD, QTD, MTD, MoM, QoQ).
- **Hierarchies and Slicers**: Enabled drill-up and drill-down functionality for products, territories, and dates.
- **Visualizations**: Developed dashboards to explore revenue trends, product performance, order statuses, and shipping metrics.

---

## Insights

1. **Sales Trends**:
   - Saturdays and Q3 were peak revenue periods.
   - July accounted for the highest monthly sales.
2. **Product Analysis**:
   - Bikes dominated revenue among product categories.
3. **Regional Performance**:
   - North America led sales, followed by Europe.
4. **Shipping Metrics**:
   - Average shipping time was consistent across categories but varied by region.
5. **Order Status**:
   - The highest number of orders by status were in "Approved" status.

---
(The report is 6 pages, these are the first three pages)
![image](https://github.com/user-attachments/assets/3f9eb318-449b-43b7-a68d-acec83b8f5ee)

![image](https://github.com/user-attachments/assets/d23b330f-e027-4a2e-bc19-fba2b74c23d7)

![image](https://github.com/user-attachments/assets/ea6e35d1-0980-42ac-962c-5e977a0b1ad4)

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/SelsabeelA/SalesDataDashboard.git
