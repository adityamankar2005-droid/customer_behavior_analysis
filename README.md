Customer Behavior Data Analytics Project
Overview

This project is an end-to-end data analytics project focused on understanding customer purchasing behavior. The aim of the project is to analyze how customers interact with products, identify buying patterns, and generate insights that can help support business decisions.

The project covers the complete analytics workflow — from loading and cleaning raw data to querying it using SQL and finally visualizing insights through a Power BI dashboard.

Dataset

The dataset contains customer-related information such as purchase history, product categories, and transaction details. It was used to analyze customer behavior, purchasing frequency, and product performance.

The dataset was first explored and cleaned using Python before being loaded into a PostgreSQL database for further analysis.

Tools & Technologies Used

Python – Used for loading the dataset, exploratory data analysis (EDA), and data cleaning

Libraries: Pandas, NumPy, Matplotlib / Seaborn

PostgreSQL – Used as the database for running analytical SQL queries

SQL – Used for aggregations, customer segmentation, and ranking analysis

Power BI – Used to build an interactive dashboard

Gamma – Used to create the project presentation (PPT)

GitHub – Used for version control and project documentation

Project Steps
1. Data Loading

  The dataset was loaded into Python using Pandas. Basic checks were performed to understand the structure of the data, column names, and data types.

2. Exploratory Data Analysis (EDA)

  EDA was performed to:

  Understand customer purchasing patterns

  Identify trends and distributions

  Detect missing values and inconsistencies

3. Data Cleaning

  During the cleaning process:

  Missing and incorrect values were handled

  Data types were corrected where required

  Categorical values were standardized

4. SQL Analysis (PostgreSQL)

After cleaning, the data was loaded into a PostgreSQL database. SQL queries were written to:

Segment customers into New, Returning, and Loyal groups

Analyze purchase frequency

Identify top products by category

Rank items using window functions

5. Power BI Dashboard

A Power BI dashboard was created by connecting directly to the PostgreSQL database. The dashboard includes:

Customer segmentation insights

Purchase behavior trends

Top-performing products per category

Key metrics presented in a clean and professional layout

6. Report & Presentation

A short analytical report was created to summarize the findings. A presentation was also built using Gamma to clearly communicate insights and conclusions.

Dashboard

The Power BI dashboard provides an interactive view of customer behavior and product performance. It is designed to be simple, readable, and suitable for business users.

(Screenshots of the dashboard are included in the repository.)

Results & Insights

Customers were successfully segmented based on purchase behavior

Key buying patterns and repeat customer trends were identified

High-performing products across different categories were highlighted

The analysis provides insights that can support marketing and sales decisions

How to Run the Project

1. Clone the repository:

   git clone <repository-link>


2. Run the Python notebooks/scripts for data loading, EDA, and cleaning

3. Load the cleaned dataset into PostgreSQL

4. Execute the SQL queries provided

5. Open the Power BI .pbix file to explore the dashboard

6. Review the report and presentation files for summarized insights

Conclusion

This project demonstrates a complete data analytics workflow, from raw data processing to delivering insights through visualization and reporting. It reflects real-world data analyst tasks and highlights skills in Python, SQL, and Power BI.
