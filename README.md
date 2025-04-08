# TASK_2-Tableau_dashboard
# Superstore Tableau Dashboard

## About Project
This project contains an interactive Tableau Dashboard created using the Superstore dataset.

## Tools Used
- Tableau
- Excel
- GitHub

## Insights
- Sales & Profit Analysis
- Region-wise Performance
- Top Customers
- Category-wise Breakdown
  
# Formulas
1.New Order Date
DATE(DATEADD('year',3,[Order Date]))
2.Current year sale
IF YEAR([New order date])=YEAR(TODAY())THEN [Sales]
END
3.Previous Year sale
IF YEAR([New order date])=YEAR(TODAY())-1 THEN [Sales]
END
4.Total Customer
COUNTD([Customer ID])
5.Total Order
COUNTD([Order ID])

# How to View Dashboard
1. Download `.twbx` file 
2. Open in Tableau Desktop



