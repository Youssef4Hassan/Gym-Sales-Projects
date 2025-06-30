 Sales-Dashboard



## Problem Statement

This dashboard helps stakeholders gain insights into sales performance.
It highlights top-performing locations and peak purchase times, along with year-over-year comparisons to identify trends in sales growth or decline. Stakeholders can track areas and times that show improvement.

The dashboard also includes churn analysis, distinguishing between new and returning customers in both sales and orders. Additionally, it provides a return analysis, offering visibility into which products are most frequently returned and from which locations. This allows stakeholders to identify weak points and uncover the root causes behind these returns.

Finally, the dashboard features a root cause analysis by category, helping identify the best-performing products that drive category sales. A summary for each product is also provided for more detailed insights.


### Steps followed 

- Step 1 : Load data into Power BI Desktop From dataset is a Excel file.
![Step 1](https://github.com/user-attachments/assets/9641c878-31f5-4f14-8ad2-7cd320a72954)
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also Check Data quality by use Captlize Each Word & Trim, detect Data type".
![Step 3](https://github.com/user-attachments/assets/26e14085-23fb-441d-92df-6795f7c625f2)

- Step 4 : Merge Queries to denormalized data & make Relocated in Fact table".

![denormalized data](https://github.com/user-attachments/assets/2084ce0e-fccb-4a3e-9498-cfe26fb08e60)


- Step 5 : load data into data model make star schema model to help us in calculation")

![Load Data](https://github.com/user-attachments/assets/e4b7a6ce-0c4d-4efc-b1dd-0947e8563b84)

![Data Model](https://github.com/user-attachments/assets/d1fd614a-a3f0-4989-a50e-3b7d4dc2a9c1)

- Step 6 : make Caluclation by DAX .

![Caluclation by DAX](https://github.com/user-attachments/assets/bbbd1e0b-3240-4b87-8198-ab18da415ae4)

- Step 7 : Build Revenue Dashboard 
Create Four Card (Revenue,Profit,cost,Quantity)
Which insights
Revenue Over time
Revenue By Country Name 
Revenue By Category 
Revenue By Business Type

![Revenue Dashboard](https://github.com/user-attachments/assets/5aba1960-e598-4b47-992c-1a83bd92de29)
. 
- Step 8 : Visual filters (Slicers) were added for Two fields named "Year", "Continent", creat arrow trend to provide change year-over-year.

![year-over-year](https://github.com/user-attachments/assets/578feaa1-5729-4335-8716-e3d4082bb200)

- Step 9 : Create Root Cause analysis for Category To Know More detailed to each category  &summary.

![product analysis](https://github.com/user-attachments/assets/5dbdded5-879f-45f6-9a9a-023c2ee9da67)


![Filters](https://github.com/user-attachments/assets/8021f6bb-4495-4f86-9b22-8e9d2b1379fb)

![summary](https://github.com/user-attachments/assets/bb3a1f04-97e6-49b7-9ad0-306c7b7e4202)

![locations analysis](https://github.com/user-attachments/assets/6dcee92a-379b-4256-8deb-fffd14001e75)
           
- Step 10 : Build Customer analysis Dashboard 
Create Four Card (Revenue,#customers,#Ordes,Quantity)
Which insights
Churn analysis
orders frequency 
#customers By month
#customers By Business Type
#customers By Continent
distinguishing between new and returning customers in both sales and orders

![Customer analysis Dashboard](https://github.com/user-attachments/assets/cc4ff429-2f4a-49b5-9dd5-b8624e28980a)


![Customer details](https://github.com/user-attachments/assets/de390c96-d770-4349-ad0f-06133a43ba12)

- Visual filters (Slicers) were added for Two fields named "Year", "Country Name", creat arrow trend to provide change year-over-year..

- Step 13 : Bulild return analysis Dashboard
Create Four Card (Revenue return,#customers return,#Ordes return,Quantity return)
Which insights
Order & Customer return by subcategory
Order & Customer return by month
Order & Customer return by Region


distinguishing between Oreder and customer returning customers By bookmarks 

![return analysis by orders](https://github.com/user-attachments/assets/863b8a7a-2c63-4928-b7a8-a52168e58872)

![return analysis by customer](https://github.com/user-attachments/assets/1974e68f-66f3-47a6-8999-4542728a5d1f)
