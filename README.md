# Pharma-Business-Analytics-Project (Excel)

## 📌 Project Overview

This project demonstrates an end-to-end Business Analytics workflow using Microsoft Excel on a simulated pharmaceutical sales dataset.

The project covers the complete analytics lifecycle, including:

- Data Cleaning
- Data Validation
- Data Transformation
- Feature Engineering
- Table Merging
- KPI Development
- Pivot Table Analytics
- Dashboard Creation
- Business Insight Generation

The objective was to transform raw pharmaceutical business data into an interactive dashboard that supports business decision-making.

---

# 📂 Project Structure

```
ZS Pharma Business Analytics/
│
├── Raw Dataset.xlsx
├── Cleaned Dataset.xlsx
├── Data Cleaning Report.docx
├── Data Analytics Report.docx
├── Dashboard Presentation.pptx
└── README.md
```

---

# 📊 Dataset Overview

The project consists of multiple related datasets representing different business functions.

| Sheet | Description |
|--------|-------------|
| Sales | Sales transactions |
| Doctors | Doctor master data |
| Products | Product catalog |
| Medical_Reps | Medical Representative details |
| CRM_Visitings | Customer visits |
| Inventory | Warehouse inventory |
| Marketing | Marketing campaign data |
| Competitor_Sales | Competitor sales data |
| Complaints | Customer complaints |
| Returns | Returned orders |

---

# 🧹 Data Cleaning Performed

The raw dataset was cleaned and standardized before analytics.

### Major Cleaning Tasks

- Removed duplicate records
- Standardized date formats using Power Query
- Converted negative quantities to positive values
- Cleaned Unit Price values
- Standardized Region and City names
- Standardized Doctor names
- Filled missing Discount values
- Filled missing Satisfaction Score values using column average
- Corrected negative Inventory Stock
- Corrected Returned Quantity values
- Validated primary keys
- Checked business constraints
- Created validation columns

### Data Validation Columns

#### Sales

- Qty_Status

#### Products

- Cost_Validation

---

# 🔗 Data Transformation

Additional analytical columns were created to support reporting.

### Sales

- Total Revenue
- Discounted Price
- MR_Name (using XLOOKUP)
- ProductName (using XLOOKUP)

### KPI Formula

Return Rate

```
(Total Returns / Total Orders) × 100
```

---

# 📈 Dashboard KPIs

The dashboard contains the following KPIs:

- Total Revenue
- Total Orders
- Total Quantity Sold
- Average Unit Selling Price
- Average Discount
- Total Active Doctors
- Total Active Medical Representatives
- Total Inventory Stock
- Return Rate
- Overperforming Medical Representatives

---

# 📊 Dashboard Visualizations

The dashboard includes:

- Monthly Sales Trend
- Revenue by Region
- Top Products
- Top 10 Medical Representatives by Revenue
- Warehouse-wise Inventory
- Stock vs Damaged Inventory
- Competitor Market Share
- Resolution Days vs Satisfaction Score

---

# 📌 Business Insights

Some major insights derived from the analysis:

- Delhi contributes the highest sales revenue.
- Product sales are fairly balanced across the portfolio.
- Competitor A holds approximately 55% market share.
- Satisfaction Score shows no strong linear relationship with Resolution Days.
- Return Rate is approximately 8%.
- Delivery is the most common complaint category.
- Around 25–30 Medical Representatives contribute significantly more revenue than the remaining workforce.

---

# 🛠 Tools & Technologies

- Microsoft Excel
- Power Query
- Pivot Tables
- Pivot Charts
- XLOOKUP
- IF
- SUBSTITUTE
- PROPER
- UPPER
- ABS
- AVERAGE
- COUNTIF
- Conditional Formatting

---

# 📚 Excel Features Used

- Power Query
- Pivot Tables
- Pivot Charts
- Slicers
- Conditional Formatting
- Data Validation
- Named Calculations
- Dashboard Design
- Excel Functions

---

# 📁 Deliverables

- ✅ Raw Dataset
- ✅ Cleaned Dataset
- ✅ Data Cleaning Documentation
- ✅ Analytics Documentation
- ✅ Interactive Excel Dashboard
- ✅ PowerPoint Presentation

---

# 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Real-world data cleaning
- Data quality assessment
- Excel-based ETL
- Business KPI creation
- Dashboard development
- Pivot Table analytics
- Business insight generation
- Pharmaceutical sales analytics

---

# 👨‍💻 Author

**Sumit Sinha**

Electronics & Computer Engineering  
Thapar Institute of Engineering & Technology

LinkedIn:
https://www.linkedin.com/in/sumit-sinha-454a232a6/

---

## ⭐ Project Summary

This project demonstrates a complete Excel-based Business Analytics workflow, beginning with raw pharmaceutical datasets and ending with a fully interactive executive dashboard. It showcases practical skills in data cleaning, transformation, feature engineering, KPI development, dashboard design, and business reporting using Microsoft Excel.
