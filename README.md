# 🍽️ Swiggy Data Analysis Dashboard – Power BI
# 📊 Project Overview

This project is an interactive Power BI dashboard built using Swiggy restaurant data.
The dashboard provides insights into orders, revenue, ratings, food categories, and city-wise performance, helping understand customer preferences and business trends.

# 🎯 Objectives

Analyze restaurant performance using KPIs

Compare Veg, Non-Veg, and Other food categories

Identify top-performing cities based on revenue

Visualize ratings, prices, and delivery insights

Enable interactive filtering using slicers

# 🧩 Dataset Details
```

The dataset contains the following attributes:

Restaurant ID

City & Area

Restaurant Name

Food Type

Price

Average Ratings

Total Ratings

Delivery Time
```

# 📈 Dashboard Features

KPI Cards

Total Orders

Total Restaurants

Total Revenue

Total Ratings

Visual Analytics

Food Category-wise Revenue

City-wise Revenue (Top-N Analysis)

Revenue Trend Visualization

Interactive Slicers

City

Area

Food Category

Professional UI

Swiggy-themed color palette

Clean layout with icons and images

User-friendly design

# 🛠️ Tools & Technologies

Power BI Desktop

DAX (Data Analysis Expressions)

Power Query

CSV Dataset

# 🧮 Key DAX Measures Used
Total Orders = COUNT('Swiggy'[ID])

Total Restaurants = DISTINCTCOUNT('Swiggy'[Restaurant])

Total Revenue = SUM('Swiggy'[Revenue])

Total Ratings = SUM('Swiggy'[Total ratings])

Average Price = AVERAGE('Swiggy'[Price])

# 🖼️ Images & Design

Swiggy logo added using Insert → Image

Food category images for better visualization

Custom dashboard background using Canvas Background

(Optional) Dynamic images using Image URL

# 📂 Project Structure
```
📁 Swiggy-PowerBI-Dashboard
 ┣ 📄 Swiggy_Dashboard.pbix
 ┣ 📄 swiggy_data.csv
 ┣ 📄 README.md
```

# 🚀 How to Use

Download the .pbix file

Open with Power BI Desktop

Refresh data if required

Use slicers to explore insights

# 🧠 Use Cases

```
Academic Mini Project

Power BI Practice Portfolio

Data Visualization Demonstration

Business Intelligence Learning
```
# Dashboard Preview



# 📌 Conclusion

This Power BI dashboard demonstrates how raw food delivery data can be transformed into meaningful business insights using effective data modeling, DAX calculations, and interactive visualizations.
