📊 Exploratory Data Analysis (EDA) 
Overview
This notebook walks through a complete Exploratory Data Analysis (EDA) process using Python. The goal is to examine and understand the structure and distribution of data found in two CSV files:

client_data.csv

price_data.csv

The analysis includes data loading, descriptive statistics, and a variety of visualizations to extract insights from both numerical and categorical features.

🧰 Libraries Used
pandas

matplotlib

seaborn

Warnings are suppressed to keep the output clean.

📁 Dataset Description
client_data.csv: Contains client-level information, both categorical and numerical.

price_data.csv: Contains pricing information, primarily numerical values.

📌 Sections Covered
Importing Required Packages
Loading libraries and setting Seaborn styling for plots.

Loading the Data
Reading the datasets into Pandas DataFrames and displaying the first few rows.

Descriptive Statistics

Overview of dataset shapes, null values, and data types

Distribution and summary statistics for numeric columns

Data Cleaning & Transformation

Handling missing values

Converting data types

Feature engineering (e.g., calculating margins)

Data Visualization

Bar plots, histograms, box plots, and stacked bar plots

Client churn and retention analysis

Margin distribution insights

Annotation Functions
Custom functions like annotate_stacked_bars() are used to enhance plot readability.

📈 Key Insights
Zero values in pricing columns might indicate missing or erroneous data.

Certain client features are heavily skewed or contain outliers.

Visualizations like stacked bar plots effectively highlight churn vs retention.

▶️ How to Run
Clone or download this repo.

Ensure the required CSV files (client_data.csv, price_data.csv) are in the same directory.

Run the notebook step-by-step in a Jupyter environment.

💡 Author Notes
This notebook provides a great foundation for building models later, as it ensures a thorough understanding of the underlying data. Visualization and transformation steps prepare the dataset for machine learning pipelines.
