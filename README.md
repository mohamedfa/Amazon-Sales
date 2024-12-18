# Amazon Sales Data Analysis

This project is focused on cleaning, exploring, analyzing, and visualizing Amazon sales data using **Excel**. The goal of this project is to generate insights from the raw data and present key metrics and trends through an interactive dashboard. Below is a summary of the steps taken during the project:

## Project Workflow

### 1. Data Cleaning

![image](https://github.com/user-attachments/assets/c283ea65-5106-43bd-bf25-9826cc8265b3)

The first step was to clean the raw sales data:
- **Transformed raw data into a table format** for easy analysis.
- **Checked column data types** to ensure consistency across the dataset.
- **Handled missing values** by checking for blanks and null entries.
- **Removed duplicate records** to ensure data integrity.
- Created a new column to calculate **Delivery Time in days**.

![image](https://github.com/user-attachments/assets/4a841576-fcee-48a7-a14e-bbbb530c66c0)

### 2. Data Preparation

After cleaning, we calculated key metrics to better understand the data. The following are some important summary statistics:
![image](https://github.com/user-attachments/assets/891278ae-c061-4f1b-b4b2-419bf19a8f1a)

- **Sum of Units Sold**: 512,871
- **Sum of Unit Price**: $27,676.13
- **Sum of Unit Cost**: $19,104.80
- **Sum of Total Revenue**: $137,348,768.31
- **Sum of Total Cost**: $93,180,569.91
- **Sum of Total Profit**: $44,168,198.40
- **Minimum Delivery Time**: 0 days (same-day delivery)
- **Maximum Delivery Time**: 50 days

### 3. Data Visualization

Next, pivot tables and charts were created to visualize the key metrics. The results were then organized into a **dashboard** with three main pages: **Overview**, **Detailed**, and **Insights**.

#### Overview Page
![image](https://github.com/user-attachments/assets/89e3340f-4a22-4a36-84c2-7318341909ce)

This page contains essential measures and high-level charts:

- **Sum of Total Revenue by Region (Bar Chart)**: Africa had the highest revenue with $40 Million.
![image](https://github.com/user-attachments/assets/a22dec14-29c9-4df9-a3a0-79cdaee47362)

- **Sum of Units Sold by Year (Line Chart)**: 2012 saw the highest number of units sold with 97,967 units.
![image](https://github.com/user-attachments/assets/b8d5e610-bd44-4aa6-bb99-f02fdcfca524)

- **Sum of Total Profit by Item Type (Column Chart)**: Cosmetics generated the highest profit with $15 Million.
![image](https://github.com/user-attachments/assets/b6b76fe7-b847-40b0-8fb4-76bf9c9802f3)

- **Sum of Units Sold by Order Priority (Doughnut Chart)**: "High priority" orders had the highest units sold (30%), followed by "Low priority" (29%).

![image](https://github.com/user-attachments/assets/c02b7f59-669d-4f1a-b136-862baf82cadf)

- **Sum of Units Sold by Sales Channel (Doughnut Chart)**: The "Offline" sales channel sold 54% of the units.

![image](https://github.com/user-attachments/assets/b4864780-1be9-4157-9d1c-ea9311fe35a4)

#### Detailed Page
![image](https://github.com/user-attachments/assets/71655d47-aa3e-4b5b-bfdd-960c3eeab734)

This page dives deeper into various metrics and their breakdowns:

- **Sum of Units Sold by Region (Bar Chart)**: Africa had the highest units sold, with over 180,000 units.
![image](https://github.com/user-attachments/assets/a52d3af4-aca4-4972-9ade-dbf1aa231ec9)

- **Sum of Total Cost, Profit, and Revenue by Year (Line Chart)**: 2012 and 2010 had similar total profits.
![image](https://github.com/user-attachments/assets/a01a282b-78ff-41c8-8a29-eaa1cf7bc5e3)

- **Sum of Total Cost, Profit, and Revenue by Item Type (Bar Chart)**: Cosmetics had the highest total revenue and profit, while office supplies had the highest total cost.

![image](https://github.com/user-attachments/assets/47b40e4e-9db3-47eb-9b4a-c609eb5fe5b8)

- **Sum of Total Revenue by Sales Channel (Doughnut Chart)**: The "Offline" sales channel accounted for 58% of total revenue.

![image](https://github.com/user-attachments/assets/ddafce76-a435-415b-9bc8-3249b1b77293)

- **Sum of Total Revenue by Order Priority (Doughnut Chart)**: "High priority" orders generated the highest revenue at $48 Million (35%), followed by "Low priority" at $36 Million (27%).

![image](https://github.com/user-attachments/assets/4be246e2-2cab-43e1-a84d-5297a921b61f)

#### Insights Page
![image](https://github.com/user-attachments/assets/ad28b23c-f6e4-4a15-83ef-9d1749c08f69)

This page includes additional measures and further insights into the data:

- **Distribution of Delivery Time (Histogram)**: The most common delivery time was between 0 and 11 days.
![image](https://github.com/user-attachments/assets/4d049d7c-2536-4e94-8c7c-892d46b3a441)

- **% Order Priorities by Region (Column Chart)**: North America, Central America, and the Caribbean had similar percentages of order priorities.

![image](https://github.com/user-attachments/assets/05fb5fde-a9e4-4091-91b0-30be552f1560)

- **Sum of Total Cost, Profit, and Revenue by Region (Line Chart)**: Detailed breakdown of cost, profit, and revenue by region.

![image](https://github.com/user-attachments/assets/7e463612-e2e0-4cd8-bad1-091f51073f6e)

- **Top 10 Countries by Sum of Units Sold (Bar Chart)**: Sao Tome and Principe had the highest sum of units sold, with more than 24,000 units.

![image](https://github.com/user-attachments/assets/b9ebb894-e5b1-40f5-8a34-b3fb5300d64c)

- **Top 10 Countries by Sum of Total Revenue (Bar Chart)**: Honduras had the highest revenue, with more than $6 Million.

![image](https://github.com/user-attachments/assets/2fd00870-a87b-4d57-ab3c-8f394844e40c)

## Interactive Dashboard

You can explore the data and interact with the dashboard through this link:  
[Amazon Sales Data Dashboard](https://onedrive.live.com/view.aspx?resid=1F453ECED1617B84%21924&authkey=!AL8SByC43YoRRKY)

## Conclusion

This project showcases how clean data can be leveraged to generate meaningful insights about Amazon sales performance. By using interactive visualizations, we can easily identify trends, key metrics, and potential areas of improvement for sales strategies.

Feel free to explore the dashboard and dive deeper into the findings!
