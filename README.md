# Sales-Dashboard-Using-Power-Bi
# Data Source:
### Sales.xlsx

# Modeling:
### - Star Schema
#### 1 Fact Table and 4 Dimension Tables (Dim Products – Dim Customers – Dim Date – Dim Shipping)
#### Dim product:	Product ID	Product Name	Postal Code	Region	Category	Sub-Category	Sales
#### Dim customers:	Customer ID	Customer Name	Segment	Country	City	State	
#### Dim Date:	Order Date	Ship Date										
#### SalesFact:	Ship Mode	Quantity	Discount	Profit	Row ID	Order ID	

### Create Measures using DAX:
### - # Orders Measure (Number of Orders)
### - Total Quantity Measure
### - Total Revenue Measure
### - Total Profit Measure
### - Average Discount

# Visuals: (Use Measures) Create a Dashboard that contains the following insights.
## 1- Cards
### - Total Quantity Measure
### - Total Revenue Measure
### - Total Profit Measure
## 2- Clustered Column
### - Total Sales by Subcategories
### - Top 10 Product Name by Sales
## 3- Pie / Donut Chart
### - Total Sales by Category
### - Total Profit by Category
## 4- Line Chart
### # Orders by Month
