# Task 2 - Unemployment Analysis with Python

## 📌 Objective
Perform exploratory data analysis (EDA) on unemployment data in India to 
uncover regional and temporal trends, with a focus on the impact of 
COVID-19 on unemployment rates.

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 Dataset
- Source: [Kaggle - Unemployment in India](https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india)
- Contains region-wise unemployment rate, employment estimates, and 
  labour participation rate across Indian states from 2019–2020.

## 🔍 Approach
1. Loaded and cleaned the dataset (handled null values, fixed column 
   formatting, converted dates)
2. Performed EDA — region-wise and month-wise unemployment averages
3. Visualized trends using:
   - Time-series line chart (unemployment rate over time by state)
   - Bar chart (top 10 states by average unemployment rate)
   - Heatmap (correlation between unemployment, employment, and labour 
     participation rate)
4. Compared pre-COVID vs post-COVID average unemployment rates

## 📈 Key Insights
- Tripura (28.35%) and Haryana (26.28%) recorded the highest average 
  unemployment rates among all regions.
- A sharp spike occurred in April 2020 (23.64%), coinciding with 
  India's COVID-19 lockdown.
- Average unemployment rate nearly doubled post-COVID — from 9.51% to 
  17.77%.
- Unemployment rate showed weak correlation with employed count (-0.22) 
  and negligible correlation with labour participation rate (0.00).

## 📁 Files
- `Balwantsingh_Task2.ipynb` — full analysis notebook
- `Unemployment_in_india.csv` — dataset used

## 🚀 How to Run
1. Clone this repository
2. Install requirements: `pip install pandas matplotlib seaborn`
3. Open `Balwantsingh_Task2.ipynb` in Jupyter Notebook and run all cells


## 👨‍💻 Author

**Balwant Singh**

B.Tech CSE (AI & ML)

Oasis Infobyte Internship Project

