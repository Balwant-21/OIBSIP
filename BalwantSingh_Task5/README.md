# Task 5 - Sales Prediction Using Python

## 📌 Objective
Build a regression model to predict product sales based on advertising 
expenditure across TV, Radio, and Newspaper channels, and identify which 
advertising channel has the greatest impact on sales.

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📊 Dataset
- Source: [Kaggle - Advertising Dataset](https://www.kaggle.com/datasets/tawfikelmetwally/advertising-dataset)
- Contains advertising budgets (in thousands of dollars) for TV, Radio, 
  and Newspaper, along with the resulting product Sales.

## 🔍 Approach
1. Loaded and cleaned the dataset (checked nulls, removed redundant index column)
2. Performed EDA:
   - Pairplot across all features
   - Individual scatter plots (Sales vs TV, Radio, Newspaper)
   - Correlation heatmap
3. Split data into training and testing sets (80/20)
4. Trained two regression models:
   - Linear Regression (baseline)
   - Random Forest Regressor
5. Evaluated both models using MAE, RMSE, and R² score
6. Generated a residual plot to validate the best-performing model
7. Analyzed feature importance to determine which advertising channel 
   drives sales the most

## 📈 Key Insights
- TV spend showed the strongest correlation with Sales (0.78), followed 
  by Radio (0.58), while Newspaper spend showed weak correlation (0.23).
- Random Forest significantly outperformed Linear Regression:
  | Metric | Linear Regression | Random Forest |
  |--------|-------------------|----------------|
  | MAE    | 1.46              | 0.62           |
  | RMSE   | 1.78              | 0.77           |
  | R²     | 0.89              | 0.98           |
- The residual plot showed randomly distributed errors with no systematic 
  pattern, confirming Random Forest as a well-fitted model.
- Feature importance confirmed TV (~60%) as the strongest driver of sales, 
  followed by Radio (~35%), with Newspaper contributing minimally (~3%).
- **Business takeaway:** Advertising budget should be prioritized toward 
  TV and Radio, as Newspaper spend shows little measurable impact on sales.

## 📁 Files
- `BalwantSingh_Task5.ipynb` — full analysis and modeling notebook
- `Advertising_data.csv` — dataset used

## 🚀 How to Run
1. Clone this repository
2. Install requirements: `pip install pandas numpy matplotlib seaborn scikit-learn`
3. Open `BalwantSingh_Task5.ipynb` in Jupyter Notebook and run all cells