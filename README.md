# 📊 Power BI Sales Analytics Dashboard – Awesome Chocolates

Welcome to the Power BI portfolio project for **Awesome Chocolates**, a fictional chocolate company. This project demonstrates a complete end-to-end Power BI solution — from data modeling to dashboard design, DAX calculations, and final report publishing.

<img width="1411" height="790" alt="image" src="https://github.com/user-attachments/assets/93630d5d-3eec-41fa-ad34-6738448bae0c" />


## 🔍 What This Project Covers

- Data modeling using a star schema  
- Creating [DAX measures](https://github.com/nsmahesh18/PBI-Sales-Dashboard/tree/main/docs), including:
  - Time intelligence calculations
  - Profit and cost calculations
- Designing interactive dashboard elements:
  - KPI cards and reference labels  
  - Conditional formatting  
  - Tooltips, bookmarks, and [field parameters](https://github.com/nsmahesh18/PBI-Sales-Dashboard/blob/main/docs/Sales%20Analytics%20Dashboard.docx)  
  - Dynamic trend charts  
  - [Grouping](https://github.com/nsmahesh18/PBI-Sales-Dashboard/blob/main/docs/Sales%20Analytics%20Dashboard.docx), histograms, zoom sliders  
  - Alert icons for key metrics  
- Analyzing key business insights:
  - Month-over-month trends  
  - Low box shipments  
  - Salesperson and product performance  

## 📁 Dataset Overview

The project uses a [sample dataset](https://github.com/nsmahesh18/PBI-Sales-Dashboard/blob/main/dataset/ac-sample-data.xlsx) covering **13 months of chocolate sales data** (Feb 2023 – Feb 2024), organized into:

- `Shipments` (Fact table)
- `Product` (Dimension)
- `Salesperson` (Dimension)
- `Locations` (Dimension)
- `Calendar` (Dimension)

Each shipment record links a product, salesperson, geography, and date to a quantity of boxes sold and the corresponding sales amount.

## 🧩 Data Model Overview

The Power BI data model follows a **star schema** with the `Shipments` table at the center, connected to four dimension tables:

<img width="842" height="564" alt="image" src="https://github.com/user-attachments/assets/a62d8b5c-374b-4fd2-ada6-ddb81b3e2986" />

NOTE: Tables names are renamed and doesn't reflect the same name as mentioned in dataset

## ✅ Final Output

The final `.pbix` file is a portfolio-ready Power BI report that can be viewed and customized by others.  
Feel free to download, explore, and reuse it for your own learning or professional projects.

## 📝 License

This project is licensed under the [MIT License](LICENSE).  
You are free to use, modify, and share this project with attribution.
