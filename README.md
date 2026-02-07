🍔 Swiggy Sales Analysis Project

📌 Project Overview

This project focuses on analyzing Swiggy food delivery sales data to understand how the business is performing and how customers behave on the platform. The analysis covers areas such as sales performance, customer ratings, food preferences, and time-based trends.
The project follows a complete end-to-end data analytics process. It starts with loading and exploring the data, followed by cleaning, KPI calculation, and detailed visual analysis using Python.
This project is created to demonstrate practical data analytics skills, business thinking, and the ability to present insights clearly. It is suitable for use in portfolios, internships, and data analyst job applications.
 
🎯 Objectives of the Project
  •	Analyze overall sales performance of Swiggy orders
  •	Calculate important business KPIs
  •	Identify time-based trends (daily, weekly, monthly, and quarterly)
  •	Compare Veg and Non-Veg food sales
  •	Analyze sales performance by state and city
  •	Understand customer ratings and ordering behavior
  •	Create clear and meaningful visualizations
 
🛠️ Tools & Technologies Used
  •	Python
  •	Jupyter Notebook
  •	Pandas – for data cleaning and analysis
  •	NumPy – for numerical calculations
  •	Matplotlib & Seaborn – for static charts
  •	Plotly Express – for interactive visualizations
  •	Excel (.xlsx) – used as the data source
 
📂 Dataset Description
The dataset contains order-level data related to Swiggy food deliveries. Some of the main columns used in the analysis are:
  •	Order Date – The date when the order was placed
  •	Price (INR) – Total value of the order
  •	Rating – Rating given by the customer
  •	Rating Count – Number of people who rated the item
  •	Food Name / Category – Type of food ordered
  •	City – City where the order was placed
  •	State – State where the order was placed
📌 The data is loaded from an Excel file named:
swiggy_data.xlsx
 
🔍 Data Exploration & Understanding
Before starting the analysis, the data was explored properly to understand its structure and quality. The following steps were performed:
  •	Viewed the top and bottom rows of the dataset
  •	Checked the total number of rows and columns
  •	Verified column data types
  •	Used .info() to check missing values and data structure
  •	Used .describe() to understand basic statistics
These steps helped ensure the data was clean and ready for further analysis.
 
📊 Key Performance Indicators (KPIs)
The following important business KPIs were calculated in the project:
1️⃣ Total Sales
  •	Calculated as the sum of all order values
  •	Helps measure overall revenue performance
2️⃣ Average Rating
  •	Average of customer ratings
  •	Shows overall customer satisfaction
3️⃣ Average Order Value (AOV)
  •	Average amount spent per order
  •	Useful for pricing and upselling decisions
4️⃣ Ratings Count
  •	Total number of ratings received
  •	Indicates customer engagement
5️⃣ Total Orders
  •	Total number of orders placed
  •	Helps understand platform activity
 
📈 Data Visualizations & Insights
📅 Monthly Sales Trend
  •	Sales grouped by year and month
  •	Helps identify growth patterns and seasonal trends
📆 Daily Sales Trend
  •	Sales analyzed by day of the week
  •	Useful for finding peak and low-demand days
🥗 Veg vs 🍗 Non-Veg Sales Analysis
  •	Food items classified using keywords
  •	Sales compared between Veg and Non-Veg categories
  •	Helps understand customer food preferences
🗺️ Sales by State
  •	Bar chart showing state-wise sales
  •	Identifies high-revenue states
📊 Quarterly Performance Summary
  •	Orders grouped by financial quarters
  •	Useful for management and strategic analysis
🏙️ Top 5 Cities by Sales
  •	Shows cities generating the highest sales
  •	Helpful for regional marketing strategies
📈 Weekly Trend Analysis
  •	Sales analyzed on a weekly basis
  •	Helps track short-term demand changes
 
💡 Business Insights Generated
  •	Clear understanding of high-performing time periods
  •	Identification of top cities and states by sales
  •	Better understanding of customer food choices
  •	Insights into customer satisfaction through ratings
These insights can help in:
  •	Promotional planning
  •	Regional expansion decisions
  •	Menu optimization
  •	Pricing strategy improvement
 
📁 Project Structure
📦 Swiggy-Sales-Analysis
│
├── Swiggy Sales Analysis.ipynb   # Jupyter Notebook with complete analysis
├── swiggy_data.xlsx             # Dataset (Excel format)
├── README.md                    # Project documentation
 
🚀 How to Run the Project
  1.	Clone the repository
git clone <repository-link>
  2.	Install the required libraries
pip install pandas numpy matplotlib seaborn plotly openpyxl
  3.	Open Jupyter Notebook
jupyter notebook
  4.	Run Swiggy Sales Analysis.ipynb
 
🔮 Future Enhancements
  •	Customer segmentation analysis
  •	Restaurant-wise performance analysis
  •	Delivery time analysis
  •	Dashboard creation using Power BI or Tableau
  •	Predictive modeling for demand forecasting
