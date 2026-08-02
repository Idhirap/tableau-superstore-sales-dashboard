# Tableau Sales Dashboard

## Overview

Interactive Tableau dashboard created to analyze sales, profit, and order trends across regions, customer segments, and customers.

## Data Source

- Microsoft Excel

## Dashboard Components

### 1. Profit by Region & Customer Segment
**Visualization:** Bar Chart

**Purpose:** Compare profitability across different regions and customer segments.

### 2. Sales Contribution by Region
**Visualization:** Pie Chart

**Purpose:** Display the percentage contribution of total sales across regions.

### 3. Order Quantity Trend
**Visualization:** Line Chart

**Purpose:** Analyze monthly order quantity trends and identify seasonal patterns.

### 4. Profit vs Sales Analysis
**Visualization:** Scatter Plot

**Purpose:** Examine the relationship between sales and profit at the customer level.

### 5. Interactive Filter

Created a calculated field based on the **Unit Price** column:

```sql
IF [Unit Price] <= 2500 THEN 'A'
ELSEIF [Unit Price] <= 5000 THEN 'B'
ELSE 'C'
END
```

#### Price Groups

| Group | Unit Price Range |
|--------|------------------|
| A | ≤ 2500 |
| B | 2501 – 5000 |
| C | > 5000 |

## Tools Used

- Tableau
- Microsoft Excel

## Dashboard Screenshot

![Dashboard Screenshot](screenshots/dashboard.png)

