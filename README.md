# customer_behavior_analysis
Data analytics project showcasing customer behavior analysis using Python, SQL and PowerBi
Overview
This project demonstrates an end-to-end data analytics workflow, starting from loading data using Python to building insights through Exploratory Data Analysis (EDA), data cleaning, SQL-based querying, and dashboard creation in Power BI. The project concludes with a final report and presentation built using Gamma. The goal is to showcase strong analytical, technical, and visualization skills in a clear and recruiter-friendly manner.

Dataset
The dataset used in this project was loaded into Python for initial exploration.
It contains information related to [describe dataset briefly – e.g., sales, customers, products, transactions].
The dataset includes multiple columns such as:

Categorical variables (e.g., region, category)
Numerical variables (e.g., revenue, quantity)
Date/time fields (e.g., order date)
The dataset was later moved into a PostgreSQL server for advanced querying.

Tools & Technologies
Python (Pandas, NumPy, Matplotlib/Seaborn) – Data loading, cleaning, EDA
PostgreSQL – SQL queries and data transformations
Power BI – Interactive dashboard creation
Gamma – Final PPT-style presentation
Jupyter Notebook / VS Code – Development environment

Steps Involved
1. Load Dataset in Python
Imported dataset using Pandas.
Verified columns, datatypes, shape, and missing values.

2. Exploratory Data Analysis (EDA)
Summary statistics (mean, median, distribution trends)
Data visualizations (bar charts, histograms, scatter plots, heatmaps)
Identified key patterns and anomalies.

3. Data Cleaning
Handled missing values using imputation.
Removed duplicates.
Standardized column names and date formats.
Created new derived columns where needed.
Exported the cleaned dataset.

4. Loading Data to PostgreSQL
Created database and table schema.
Loaded cleaned dataset into PostgreSQL.
Performed SQL queries for:
Aggregations
Joins
Window functions
Business insights

5. Power BI Dashboard
Imported cleaned PostgreSQL dataset.
Built an interactive dashboard including:
KPIs
Filters & slicers
Trend charts
Category-level breakdown

6. Report & Presentation
Summarized insights extracted from Python, SQL, and Power BI.
Prepared a final report.
Designed a clean, professional slide deck using Gamma.
Dashboard Overview
The Power BI dashboard highlights:
Overall business performance
Key metrics and KPIs
Trends over time

Comparisons between categories/regions/products
Interactive filtering capabilities for deeper analysis
Results / Key Insights

Identified major factors influencing performance.
Highlighted categories/segments with strong and weak performance.
Discovered trends, seasonality, and patterns in the data.
Provided actionable insights for decision-making.

How to Run the Project
1. Clone the repository
git clone <repository_url>
cd project-folder

2. Install required Python packages
pip install -r requirements.txt

3. Run the Python notebook
Open notebook.ipynb or analysis.ipynb.
Execute all cells for data loading, EDA, and cleaning.

4. Set up PostgreSQL

Create a database.
Import the cleaned dataset using COPY or SQLAlchemy.
Run queries in the sql_queries.sql file.

5. View Power BI Dashboard
Open the .pbix file in Power BI Desktop.

6. Review Final Report & Presentation
Open the PDF report.

View presentation created using Gamma.
Contact

For questions or collaboration: Email: arghajob2025@gmail.com
