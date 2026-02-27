# data-projects
This repository contains end to end data analysis projects from the Google Data Analytics Capstone and independent work. Focused on large dataset handling, memory efficient processing, SQL integration, and extracting actionable business insights using Python, Pandas, SQLite, and Excel.

 Projects Overview

My first end-to-end data analysis project from the Google Data Analytics Capstone: Case Study 1 – How does a bike-share navigate speedy success?. The project focuses on memory-efficient processing of large datasets, SQL integration, and extracting actionable business insights.


## Dataset
- **Source:** Public dataset provided as part of the Google Data Analytics Certificate  
- **Size:** ~1.2 GB, 14 million rows, 14 columns  
- **Data Quality Issues:**  
  - Null values  
  - Missing necessary columns  
  - Unnecessary columns  
  - Incorrect datatypes  
  - Messy timestamps  
  - Performance constraints  

---

## Technical Implementation
- **Memory Efficiency:** Used `pandas` chunk loading to process large CSVs without exhausting RAM, reducing memory usage from 27 GB to 4.1 GB  
- **SQLite Integration:** Used SQLite for aggregations and database operations because pandas alone cannot efficiently handle large-scale datasets  
- **Performance Optimizations:** Removed unnecessary loops, optimized `dtype` usage, separated raw vs processed data to avoid reloading large datasets repeatedly  
- **Data Cleaning & Transformation:** Handled missing values, converted datatypes, and created new calculated columns  

---

## Analysis
The project answers three key questions:

## 1. Usage Differences  
### How Annual Members and Casual Riders Use Cyclistic Bikes Differently

| Metric                    | Members                         | Casual                          |
|---------------------------|---------------------------------|----------------------------------|
| Total Rides               | 3,553,477                       | 1,999,488                        |
| Average Ride Duration     | 12.33 minutes                   | 22.59 minutes                    |
| Peak Hours                | 8 AM and 5–6 PM (commute time) | 4–6 PM (late afternoon)          |
| Busiest Days              | Thursday and Tuesday            | Saturday                         |
| Weekday vs Weekend Usage  | Heavy weekday usage             | Higher weekend proportion        |
| Ride Type Preference      | Electric bikes                  | Classic bikes                    |

### 2. Conversion Potential  
**Why casual riders might buy annual memberships**

- Frequent casual riders spend more per ride than members  
- Cost-saving opportunities suggest conversion potential  

### 3. Marketing Strategy  
**How Cyclistic can use digital media to influence casual riders**

- Promote **cost-saving benefits** of annual membership  
- Target weekend and leisure-focused riders  
- Use behavior-based digital advertising campaigns  

### Visualizations
- Pie charts  
- Bar charts  
- Line charts  
- Grouped bar charts  

**Tools Used:**  
`python` `numpy` `pandas` `matplotlib` `seaborn` `plotly` `sqlite3` `os`
