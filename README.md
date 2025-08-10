# StudentDataset-Tableau
Data Visualization with Tableau:
This project demonstrates a complete data analysis pipeline — from raw, messy data to insightful visualizations.
Using Python in Jupyter Notebook for data cleaning and Tableau for visualization, I analyzed student data from five different datasets to uncover meaningful patterns and relationships.

# Pipeline Workflow
  1. Messy Raw Data
     - Started with 5 CSV datasets containing uncleaned student data with missing values, inconsistent formats, and duplicate records.
  2. Data Cleaning in Jupyter Notebook
     - Utilized Pandas to:
     - Remove duplicates
     - Handle missing values
     - Standardize formats (dates, text casing, numerical formats)
     - Ensure consistent column naming across datasets
  3. Export Clean Data
     - Saved each cleaned DataFrame into a separate CSV file for import into Tableau.
  4. Data Integration in Tableau
     - Imported all cleaned CSVs into Tableau.
     - Created relationships between datasets instead of traditional joins to maintain data granularity and flexibility.
  5. Data Visualization & Insights
     - Built interactive dashboards to explore trends in student performance, attendance, demographics, and other relevant metrics.

# Tools & Technologies
  - Python 3
  - Jupyter Notebook
  - Pandas
  - Tableau
