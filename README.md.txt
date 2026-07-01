Unemployment Analysis with Python

#Project Overview

This project analyzes unemployment trends in India using Python. It includes data cleaning, exploratory data analysis (EDA), and data visualization to understand unemployment patterns across different states and over time. The project also examines the impact of the Covid-19 pandemic on unemployment rates.

## Objectives

- Analyze unemployment rate data.
- Perform data cleaning and preprocessing.
- Explore unemployment trends using visualizations.
- Study the impact of Covid-19 on unemployment.
- Identify state-wise unemployment patterns.
- Present insights that can support economic and social policy decisions.

##Dataset

**Dataset:** `Unemployment_Rate_upto_11_2020.csv`

The dataset contains information such as:

- Date
- Region (State)
- Estimated Unemployment Rate (%)
- Estimated Employed
- Estimated Labour Participation Rate (%)
- Area (Urban/Rural)

##Technologies Used

- Python
- Jupyter Notebook

### Python Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Workflow

1. Import libraries
2. Load the dataset
3. Explore the dataset
4. Clean the data
5. Convert date column into datetime format
6. Perform exploratory data analysis (EDA)
7. Create visualizations
8. Analyze Covid-19 impact
9. Draw conclusions

## Visualizations

The project includes the following graphs:

- Monthly Unemployment Trend
- Top 10 States by Average Unemployment Rate
- Covid-19 Impact on Unemployment

Screenshots of these graphs are available in the `images` folder.

## Key Insights

- Unemployment increased significantly during the Covid-19 pandemic.
- Some states recorded consistently higher unemployment rates than others.
- The highest unemployment levels were observed during the lockdown period.
- Unemployment gradually declined after restrictions were eased.
- Data visualization helps understand employment trends more effectively.

## Project Structure

Unemployment_Analysis/
│
├── Unemployment_Analysis.ipynb
├── Unemployment_Rate_upto_11_2020.csv
├── README.md
├── requirements.txt
└── images/
    ├── unemployment_trend.png
    ├── state_wise.png
    └── covid_impact.png
```

---

## How to Run the Project

1. Download or clone this repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook
```

4. Open `Unemployment_Analysis.ipynb` and run all the cells.

---

##Results

This analysis shows how unemployment changed over time and highlights the significant impact of Covid-19 on employment in India through data visualization and statistical analysis.
