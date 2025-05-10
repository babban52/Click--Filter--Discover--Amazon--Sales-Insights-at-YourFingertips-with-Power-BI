<div align="center">
  <img src="https://github.com/babban52/Click--Filter--Discover--Amazon-Sales-Insights-at-Your-Fingertips-with-Power-BI/blob/main/Amazon%20logo.png" alt="HDFC Logo" width="180" height="80" style="float: left; margin-right: 10 px;">
  <p> <b>Amazon</b> - Click, Filter, Discover: Amazon Sales Insights at Your Fingertips with Power BI.</p>
</div>

### Amazon Sales Analysis Dashboard

### 📌 Project Overview

This Power BI dashboard project is designed to analyze and visualize sales performance within Amazon’s fashion category. It equips business users and analysts with clear, actionable insights into product trends, sales volumes, and customer behavior—making data exploration simple and intuitive.

---

### 📂 Dataset

This project uses two main data sources:

- **Amazon Fashion Sales Data** (CSV format)
- **Amazon Sales Report** (Excel format with ASIN integration)

---

### 🚀 Key Features

- **Interactive Visuals**: Track sales performance over time and across categories
- **Category Slicers**: Filter visuals by product categories
- **Search Bar**: Instantly find products by name
- **KPI Cards**: View key performance indicators (sales, units sold, seller count)
- **Product View Page**: See product-level images, reviews, and details
- **Dynamic Navigation**: Navigate seamlessly across dashboard pages

---

### 🔄 Steps Involved

**1. Data Import & Transformation**
- Loaded the Amazon fashion CSV file and cleaned the data
- Extracted image URLs and handled null category entries

**2. Data Preparation with Power Query**
- Removed unnecessary columns
- Created custom columns for cleaner visualization
- Applied transformations and closed queries

**3. Visual Setup**
- Created slicers for category and image filtering
- Implemented a search bar for product-level access
- Added navigation buttons for smoother user experience

**4. Data Integration**
- Transformed Excel sales report (using first row as headers)
- Merged sales data with product data using ASIN as a common key

**5. DAX Calculations**
- Built custom measures: total sales, total units, and seller count
- Developed dynamic filters responding to slicers

**6. Data Visualization**
- Used clustered bar charts, area charts, and KPI cards
- Designed layout to show high-level and detailed views

**7. Tooltip Product Page**
- Created a tooltip page for individual product insights
- Synced slicers for consistent filtering across dashboard views

**8. Review Handling**
- Handled missing review data by displaying zero instead of blanks

---

### 🧭 Dashboard Navigation

The dashboard consists of three main pages:

- **Overview**: High-level metrics and trend summary  
  [🔗 View Page](https://github.com/babban52/Click--Filter--Discover--Amazon-Sales-Insights-at-Your-Fingertips-with-Power-BI/blob/main/Amazon%20Dashboard%20PDF_page-0001.jpg)

- **Products**: Detailed product-wise sales breakdown  
  [🔗 View Page]([https://github.com/jeevan499/Power-Bi-Projects-/blob/main/Amazon%20Dashboard/Amazon%20Dashboard%20PDF_page-0002.jpg](https://github.com/babban52/Click--Filter--Discover--Amazon-Sales-Insights-at-Your-Fingertips-with-Power-BI/blob/main/Amazon%20Dashboard%20PDF_page-0002.jpg))

- **Product View**: Individual product reviews, images, and sales data  
  [🔗 View Page]([https://github.com/jeevan499/Power-Bi-Projects-/blob/main/Amazon%20Dashboard/Amazon%20Dashboard%20PDF_page-0003.jpg](https://github.com/babban52/Click--Filter--Discover--Amazon-Sales-Insights-at-Your-Fingertips-with-Power-BI/blob/main/Amazon%20Dashboard%20PDF_page-0003.jpg))

---

### 🛠 Technologies Used

- **Power BI** – For data visualization and interactive dashboard creation  
- **Power Query** – For data transformation and cleansing  
- **DAX** – For custom metrics, calculations, and logic

---

### 📌 Conclusion

This Amazon Fashion Sales Dashboard transforms raw sales data into insightful, visually compelling analytics. With advanced filtering, search, and product-level views, it empowers users to quickly understand performance trends, identify opportunities, and drive better business decisions in the fast-paced world of e-commerce.

---
