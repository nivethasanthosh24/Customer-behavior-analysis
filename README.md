# Customer-behavior-analysis
Data analysis project showcasing customer behavior analysis using python, sql and powerBI

Overview

This project demonstrates an end-to-end Data Analytics workflow starting from raw dataset processing to building an interactive dashboard and final presentation.

The objective of this project is to:

* Load and analyze a dataset using Python
* Perform Exploratory Data Analysis (EDA)
* Clean and preprocess the data
* Execute SQL queries using PostgreSQL
* Build an interactive Power BI dashboard
* Generate a detailed analytical report
* Present insights through a professional PowerPoint

This project reflects real-world analytics processes used in industry.

Dataset

* The dataset contains structured data relevant to business analysis.
* It includes categorical and numerical features.
* Data was analyzed for:

  * Missing values
  * Outliers
  * Inconsistencies
  * Trends and patterns

 Tools & Technologies Used

| Tool                 | Purpose                        |
| -------------------- | ------------------------------ |
| Python               | Data loading, EDA, cleaning    |
| Pandas               | Data manipulation              |
| Matplotlib / Seaborn | Data visualization             |
| PostgreSQL           | SQL querying & data extraction |
| Power BI             | Interactive dashboard creation |
| MS PowerPoint        | Final presentation             |
| MS Word / PDF        | Analytical report              |

  Project Workflow / Steps

 Data Loading (Python)

* Imported dataset using Pandas
* Checked data types and structure
* Viewed summary statistics

 Exploratory Data Analysis (EDA)

* Identified missing values
* Detected outliers
* Analyzed feature distributions
* Studied correlations
* Created visualizations

 Data Cleaning

* Handled missing values
* Removed duplicates
* Treated outliers
* Standardized column names
* Converted data types where required

 SQL Analysis (PostgreSQL)

* Imported cleaned dataset into PostgreSQL
* Executed SQL queries:

  * Aggregations (SUM, AVG, COUNT)
  * Group By analysis
  * Filtering and sorting
  * Subqueries
  * Joins (if applicable)
* Extracted business insights using SQL

 Dashboard Creation (Power BI)

* Connected Power BI to dataset
* Created calculated columns/measures
* Built interactive visuals:

  * Bar charts
  * Line charts
  * KPI cards
  * Filters / Slicers
* Designed a clean, business-focused layout

 Report & Presentation

* Documented:

  * Data cleaning steps
  * SQL queries
  * Insights
  * Key findings
    
* Created a professional PPT summarizing:

  * Problem statement
  * Methodology
  * Dashboard insights
  * Business recommendations

Dashboard Features

The Power BI dashboard includes:

* KPI Summary
* Trend Analysis
* Category-wise Performance
* Comparative Analysis
* Region-wise Insights (if applicable)
* Interactive filters for dynamic exploration

The dashboard helps stakeholders quickly understand key metrics and performance trends.

Key Results & Insights

* Identified major performance drivers
* Detected patterns and trends in data
* Highlighted high-performing segments
* Provided actionable business recommendations
* Transformed raw data into decision-support insights

 How to Run This Project

 Python Part

1. Install required libraries:

   
   pip install pandas matplotlib seaborn psycopg2
  
2. Run the Python script:

  
   python main.py
 

 PostgreSQL Part

1. Create a database in PostgreSQL.
2. Import the cleaned dataset (CSV).
3. Run SQL queries from the provided `.sql` file.

 Power BI

1. Open the `.pbix` file.
2. Refresh data source (if needed).
3. Explore dashboard visuals.

Project Structure


├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
├── python_scripts/
│   └── eda_cleaning.py
├── sql/
│   └── analysis_queries.sql
├── powerbi/
│   └── dashboard.pbix
├── report/
│   └── final_report.pdf
├── presentation/
│   └── project_presentation.pptx
└── README.md
 Conclusion

This project demonstrates:

* Strong data preprocessing skills
* Practical SQL querying ability
* Business-oriented dashboard development
* Clear communication of insights

