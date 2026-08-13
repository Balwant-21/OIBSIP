# Task 3 - Car Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts the selling price of used cars using Machine Learning. The dataset was cleaned, analyzed, and preprocessed before training multiple regression models. The performance of the models was evaluated using standard regression metrics, and the best-performing model was identified.

---

## 🎯 Objectives

- Analyze the used car dataset.
- Perform data cleaning and preprocessing.
- Conduct Exploratory Data Analysis (EDA).
- Engineer new features to improve model performance.
- Train and compare multiple regression models.
- Identify the most important features affecting car prices.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Dataset

This project uses the **Vehicle Dataset from CarDekho** available on Kaggle.

- **Dataset Name:** Vehicle Dataset from CarDekho
- **Source:** Kaggle
- **File Used:** `Car_details_v3.csv`

**Dataset Link:**  
https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho

---

## 📂 Project Workflow

### 1. Data Preprocessing
- Loaded the dataset
- Checked dataset information
- Handled missing values
- Removed duplicate records
- Standardized categorical values

### 2. Feature Engineering
- Created **Brand** feature from the car name
- Created **Car Age** feature using manufacturing year

### 3. Exploratory Data Analysis (EDA)
- Selling Price Distribution
- Selling Price vs Fuel Type
- Selling Price vs Car Age
- Correlation Heatmap

### 4. Data Encoding
- Applied One-Hot Encoding to categorical variables

### 5. Model Training
Two regression models were trained:

- Linear Regression
- Random Forest Regressor

### 6. Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📊 Model Performance

| Model | MAE | RMSE | R² Score |
|------|-----------:|------------:|---------:|
| Linear Regression | 155,205.48 | 260,334.05 | 0.6911 |
| Random Forest Regressor | 122,308.50 | 208,422.58 | 0.8020 |

---

## 📈 Feature Importance

Random Forest Feature Importance was used to identify the most influential features affecting the selling price of used cars.

---

## ✅ Results

- Successfully built and evaluated two regression models.
- Random Forest Regressor achieved the best performance.
- Feature engineering and preprocessing significantly improved the model's predictive capability.

---

## 📁 Project Structure

```
BalwantSingh_Task3/
│
├── BalwantSingh_Task3.ipynb
├── Car_details_v3.csv
├── README.md
```

---

## 🚀 How to Run

1. Download or clone this repository.
2. Make sure the following files are in the same folder:
   - `BalwantSingh_Task3.ipynb`
   - `Car_details_v3.csv`
   - `README.md`
3. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
4. Open `BalwantSingh_Task3.ipynb` in Jupyter Notebook.
5. Run all cells sequentially to reproduce the results.

---

## 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV
- Try advanced boosting models such as XGBoost, LightGBM, or CatBoost
- Deploy the model using Flask or Streamlit
- Build an interactive web application for real-time price prediction

---

## 👨‍💻 Author

**Balwant Singh**

B.Tech CSE (AI & ML)

Oasis Infobyte Internship Project

