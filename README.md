# COVID-deaths-and-vaccinations-data-analysis
Data analysis project of COVID deaths and vaccinations for my portfolio

## Overview
Goal of this project is to hone my data analysis skills through analysing the COVID deaths and vaccinations dataset to learn how effective the vaccinations were in preventing the spread of infection, with focus on how Finland fared compared to other countries. I will be using some of the most popular tools for data analysis to clean, analyze and visualize the key takeaways from this dataset.
- **Source**: [https://docs.owid.io/projects/etl/api/covid/#download-data]
- **Description**: [list of countries, population numbers, number of COVID cases and vaccinations from start of 2020 to end of april 2021]
- **Format**: CSV

## Technologies Used
- Google sheets
- BigQuery
- Tableau

## Project Structure
```
📂 COVID-early-vaccinations-analysis
│-- 📂 CovidDeaths.xlsx               # Raw data
│-- 📂 CovidVaccinations.xlsx         # Raw data
│-- README.md                          # Project documentation
│-- SQL Queries                        # SQL queries used in project
```

## Key Steps
1. Data Cleaning: We begin by cleaning the data, making sure it is accurate and usable. This is done in gogole sheets, using the clean data function eliminate duplicates and filters to find out possible empty fields. The data is found to be clean and no actions needed to be taken. All the data is then imported to Biqguery and verified to be functioning there.

2. Exploratory Data Analysis (EDA): Using sql queries, the data was parsed through and relevant queries were made into views for visualization and further analysis. The Queries used can be found in the SQL queries folder in this repository.
   
3. Data Visualization: An interactive dashboard was created in Tableau: https://public.tableau.com/app/profile/juha.timonen/viz/Covidearlyvaccinationeffectdata/Dashboard1

4. Conclusions: Summarizing findings and potential next steps.


## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis:
   ```bash
   jupyter notebook
   ```
