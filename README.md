# COVID-19 Data Analysis using Python

## 📌 Project Overview

This project performs **COVID-19 data extraction, cleaning, analysis, and visualization using Python**.

The data is extracted from the Worldometer Coronavirus webpage using **BeautifulSoup**, processed using **Pandas and NumPy**, and visualized using **Matplotlib and Seaborn**.

## 🛠️ Technologies Used

- Python
- BeautifulSoup
- Requests
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔄 Project Workflow

1. Extracted COVID-19 country-wise data from Worldometer using BeautifulSoup.
2. Created a Pandas DataFrame from the extracted data.
3. Selected the required columns.
4. Removed unnecessary rows such as world and continent-level data.
5. Cleaned and converted numerical data.
6. Used NumPy to calculate:
   - Death Rate
   - Recovery Rate
   - Active Case Rate
7. Performed basic data analysis using Pandas.
8. Created visualizations using Matplotlib and Seaborn.
9. Created a correlation heatmap to analyze relationships between variables.
10. Saved the cleaned dataset as a CSV file.

## 📊 Visualizations

The project includes:

- Top 10 countries by COVID-19 cases
- COVID-19 cases vs deaths scatter plot
- Correlation heatmap
- Top 10 countries by COVID-19 death rate


├── covid_project.ipynb
├── covid_cleaned_data.csv
└── README.md
