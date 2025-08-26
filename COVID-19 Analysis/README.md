
# COVID-19 Data Analysis and Visualization

This project provides a comprehensive analysis of the global COVID-19 pandemic using Python. It covers data cleaning, processing, and visualization to uncover key trends and insights about confirmed cases, deaths, and recoveries across different countries and globally.

## 📌 Project Overview

COVID-19 significantly impacted the world beginning in early 2020. This project aims to:

- Track global COVID-19 cumulative cases (confirmed, recovered, and deaths).

- Perform country-wise analysis with India as an example.

- Provide an interactive country comparison (India, US, Canada, Italy, and Spain).

- Display the spread of COVID-19 across the top 20 affected countries using a heatmap.

- Generate data-driven insights about the pandemic.

## 📂 Folder Structure

```bash
COVID19-Analysis/
│
├── data/
│   └── covid_19_data.csv         # Dataset used
│
├── output images/                       # Output plots and visualizations
│   ├── global_trends.png
│   ├── india_cases.png
│   ├── global_comparison.png
│   └── covid_heatmap.png
│
├── notebooks/
│   └── covid_analysis.ipynb      # Jupyter notebook with full code
│
│
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
```
## ⚙️ Requirements
Install the dependencies with:
```bash 
pip install -r requirements.txt
```
## requirements.txt
```bash
numpy
pandas
matplotlib
seaborn
plotly
```

## 📊 Visualizations

### 1. Global COVID-19 Cumulative Cases

### 2. COVID-19 Cases in India

### 3. COVID-19 Confirmed Cases Comparison

### 4. COVID-19 Spread Heatmap


## 📈 Insights

- Global Surge: COVID-19 cases grew exponentially after March 2020, with multiple peaks.

- Hardest-hit Nations: The US and India recorded the highest confirmed cases.

- Recovery Trends: Recovery rates improved globally, but mortality patterns varied by region.

- Geographic Spread: Heatmap analysis highlights sharp increases in countries like Argentina and India.

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/Hariharan-T27/covid19-data-analysis.git
cd COVID-19_Analysis
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the script:
```bash
python scripts/covid_analysis.py
```

4. Or open the Jupyter Notebook:
```bash
jupyter notebook notebooks/covid_analysis.ipynb
```

## 📜 License
This project is for educational purposes and uses publicly available COVID-19 data.


