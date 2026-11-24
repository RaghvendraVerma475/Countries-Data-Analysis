# 🌍 Countries Data Analysis

A beginner-friendly Exploratory Data Analysis (EDA) project on world countries data using Python and Pandas.

## 📌 Project Overview
This project explores data from 194 countries across 64 features, covering population, economy, democracy, energy, emissions, healthcare, geography, and political leadership.

The analysis uses Python and Pandas to perform data filtering, sorting, aggregation, and missing-value analysis to answer real-world questions about countries.

## 📂 Project Structure

```text
Countries-Data-Analysis/
│
├── Countries.ipynb
├── Data Sets/
│   └── Countries.csv
│
└── README.md
```

## 📊 Dataset Details

- **Total Countries:** 194
- **Total Features:** 64
- **Missing Values:** Political leader and title information are missing for 7 countries.

### Key Features

| Category | Columns |
|---|---|
| General | country, country_long, capital_city, region, continent, currency |
| Economy | gdp, inflation, unemployment_pct, tax_revenue_pct_gdp |
| Population | population, population_male, population_female, median_age, birth_rate |
| Politics | democracy_score, democracy_type, political_leader, title |
| Environment & Energy | co2_emissions, forest_area, renewable_energy_consumption_pct |
| Health | life_expectancy, hospital_beds, health_expenditure_pct_gdp |

## ❓ Questions Answered

1. Which country has the highest population, and what is its capital?
2. Which country has the lowest population, and what is its capital?
3. Which are the top 5 countries by democracy score?
4. How many regions are there in total?
5. How many countries are in the Eastern Europe region?
6. Who is the political leader of the second most populated country?
7. How many countries have no political leader data available?
8. How many countries have "Republic" in their full name?
9. Which African country has the highest population?

## 🛠️ Technologies Used

- Python 3
- NumPy
- Pandas
- Jupyter Notebook

## 🚀 How to Run the Project

**1. Clone the repository**

```bash
git clone <your-repository-link>
cd Countries-Data-Analysis
```

**2. Install the required libraries**

```bash
pip install numpy pandas jupyter
```

**3. Launch Jupyter Notebook**

```bash
jupyter notebook Countries.ipynb
```

**4. Load the dataset**

Make sure `Countries.csv` is available inside the `Data Sets/` folder, as the notebook reads the dataset from this location.

## 🧠 Concepts Practiced

- Reading CSV files using `read_csv()`
- Exploring datasets using `shape`, `info()`, and `describe()`
- Boolean indexing and filtering
- Sorting data using `sort_values()`
- Finding top records using `nlargest()`
- Counting categories using `value_counts()`
- Identifying missing values using `isna()`
- Applying custom functions using `apply()`

## 🎯 Project Objective

The main objective of this project is to strengthen practical Python and Pandas skills by working with real-world country-level data and performing basic exploratory data analysis.

## 👤 Author

**Raghvendra Verma**

GitHub: https://github.com/RaghvendraVerma475

