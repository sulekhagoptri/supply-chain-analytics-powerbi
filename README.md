Project Overview

This project provides a comprehensive Supply Chain Analytics Dashboard built using Power BI.

It helps organizations monitor and optimize:

Inventory levels,
Order fulfillment,
Supplier performance,
Shipping & logistics,
Overall supply chain cost,

The dashboard is divided into 6 interactive pages, each providing actionable insights for business decision-making.
Dashboard Pages

1. Executive Summary

✔ High-level KPIs
✔ Revenue trend
✔ Orders trend
✔ Cost trend
✔ Top 10 products
✔ Top 10 locations

2️. Inventory Dashboard

✔ Inventory levels over time
✔ Stock distribution by product
✔ Warehouse analysis
✔ Safety stock vs reorder point
✔ Low stock alerts

3️. Order Fulfillment

✔ Order status breakdown
✔ On-time delivery rate
✔ Orders trend
✔ Product demand analysis
✔ Customer behavior insights

4️. Supplier Performance

✔ Supplier delivery time
✔ Defect rate
✔ Supplier cost analysis
✔ Supplier ranking
✔ Supplier scorecard

5️. Shipping & Logistics

✔ Shipping cost by carrier
✔ Transit time by route
✔ Delivery status breakdown
✔ Route performance insights

6️.. Supply Chain Cost Analysis

✔ Cost distribution
✔ Monthly cost trend
✔ Transportation vs warehousing cost
✔ Opportunities for cost reduction

Key Insights
1. Executive Summary

On-time delivery = 82% (needs improvement).
Supplier delivery is quick (~2.6 days).
Defect rate extremely low (1%).
Supply chain cost fluctuates seasonally.

2. Inventory

Certain products are overstocked.
A few products are near or below the reorder point.
One warehouse holds most of the inventory → imbalance.

3. Orders

Seasonal increase in orders during mid-year.
High demand for key SKUs.
Late deliveries observed in some months.

4. Suppliers

Most suppliers deliver on time.
One supplier shows higher defect rate.
Supplier cost differences are significant.

5. Shipping

Some carriers are significantly more expensive.
Certain routes have long transit times.
Delayed deliveries linked to route inefficiencies.

6. Costs

Transportation is a major portion of supply chain cost.
Manufacturing cost remains stable.
Inventory holding cost spikes during peak-demand periods.

 Technical Details

 Data Model

A clean star schema with:
Fact Tables: Orders, Inventory, Supplier Performance, Shipping, Costs
Dimension Tables: Products, Suppliers, Date

 Key Relationships

ProductID → Orders, Inventory, SupplierPerformance
SupplierID → SupplierPerformance
OrderID → Shipping
Date → All fact tables

📐 DAX Measures

Includes:

1.Total Revenue

2.Total Orders

3.On-Time Delivery Rate

4.Total Inventory Level

5.Avg Supplier Delivery Time

6.Avg Defect Rate

7.Total Shipping Cost

8.Total Supply Chain Cost

And many more.

 Tools Used

Power BI Desktop

Excel / CSV (Dataset)

DAX (Data modeling & measures)

ReportLab / Microsoft Word (Documentation)

Conclusion

This project delivers a full end-to-end solution for Supply Chain Analysis.
It helps organizations:
Reduce cost

Improve delivery performance

Optimize inventory

Strengthen supplier relationships

Enhance customer satisfaction

Author
Konakanchi Sulekha
