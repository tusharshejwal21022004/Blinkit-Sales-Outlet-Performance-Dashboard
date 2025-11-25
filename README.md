
Project Report: Blinkit Sales & Outlet Performance Dashboard
Prepared By: Tushar Shejwal 
Role: Data Analyst 
Tools Used: Python, Pandas, NumPy, Matplotlib,PowerBI
Domain: Retail & FMCG Analytics (Blinkit Grocery App)

1.	Project Overview
 
This Power BI dashboard provides an in-depth analysis of Blinkit’s retail performance based on sales, product categories, outlet characteristics, customer ratings, and item attributes. The objective is to uncover insights that support decision-making across inventory, outlet management, and customer experience.


2.	Business Objective 

The primary objective of this project was to answer a key business question: “How do product categories, outlet characteristics, and customer ratings impact Blinkit’s overall sales performance?” 

Blinkit, as a quick-commerce retailer, operates in a highly competitive market where sales patterns, customer satisfaction, and outlet efficiency directly influence business growth. 

•	Improve sales performance
•	Enhance customer satisfaction 
•	Optimize outlet strategy 
•	Support business decisions with data-backed insights 


3.	Dataset Description 

The dataset contains retail transaction information with fields including Item Identifier, Item Type, Item Weight, Item Visibility, Item Fat Content, Item Rating, Outlet Establishment Year, Outlet Size, Outlet Type, and Sales.

Rows: 8,524 Columns: 12




4.	Data Cleaning & Preprocessing
To ensure accurate analysis, the dataset was cleaned using Python: 

✔ Missing Values Handled

• Missing values in Item Weight → filled using mean/median
• Blank values in Item Visibility → replaced with average value
• Checked for null values in important columns and handled accordingly
________________________________________
✔ Incorrect Data Types Fixed

• Converted Outlet Establishment Year → integer
• Ensured numeric columns (Item MRP, Rating, Sales) were in correct numeric format
• Cleaned any unwanted characters from numeric fields
________________________________________
✔ Standardized Categorical Columns

The categorical columns were cleaned to ensure consistency by:
• Standardizing Item Fat Content (LF → Low Fat, reg → Regular)
• Cleaning and unifying Item Type labels
• Formatting Outlet Size and Outlet Type values for clarity
________________________________________
✔ Duplicates & Invalid Rows Removed
• Removed duplicate records
• Ensured there were no invalid or zero-sales rows


5. Exploratory Data Analysis (EDA) 

5.1	Visualizations Used 

•	Donut Chart: Customer Segmentation by Tenure 
•	Histogram: Distribution of Item Weight
•	Histogram: Distribution of Item MRP
•	 Bar Chart: Sales comparison by Item Type
•	Bar Chart: Sales comparison by Outlet Size
•	Bar Chart: Sales by Item Fat Content
•	Count Plot: Frequency of Item Types
•	Count Plot: Outlet Size distribution
•	Heatmap (Correlation Matrix) : Relationship between numeric variables





6.	Power BI Dashboard Development

After cleaning the data in Jupyter Notebook, the cleaned file (blinkit_cleaned.csv) was loaded into Power BI to create the dashboard.

✔ Data Imported & Checked
• Loaded the cleaned CSV file into Power BI
• Verified all columns and data types
• Formatted numeric fields like Sales, MRP, and Ratings
________________________________________
✔ KPI Cards Created
• Total Sales
• Average Rating
• Average Item Weight
• Total Item Types
These cards give a quick summary of overall performance.
________________________________________
✔ Visuals Added for Analysis
• Bar Chart → Sales by Item Type
• Donut Chart → Sales percentage by Item Type
• Heatmap → Average Rating by Item Type
• Line Chart → Sales by Outlet Establishment Year
• Column Chart → Sales by Outlet Size
________________________________________
✔ Filters (Slicers) Applied
• Item Fat Content
• Outlet Type
These allow users to interact with the dashboard.

6. Conclusion 

The project successfully highlights how different product categories, outlet sizes, outlet types, and customer ratings impact overall Blinkit sales performance. The analysis gives a clear understanding of which items sell the most, which outlets perform better, and how Customer satisfaction (ratings) varies across categories.
These insights help businesses make better decisions about inventory, outlet planning, and product improvements.

This project strengthened my skills in:

• Data Cleaning & Preprocessing
• Exploratory Data Analysis (EDA)
• Business Understanding
• Insight Generation
• Dashboard Creation in Power BI
• Data Visualization & Storytelling
