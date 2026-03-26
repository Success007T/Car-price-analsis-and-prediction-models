# 🚗 Car Price Prediction

A machine learning project that predicts the price of a car based on various features such as make, model, manufacturing, mileage, age, and other specifications.  
The goal of this project is to build and evaluate regression models capable of accurately estimating car prices.

---

# 📌 Project Overview

This project explores a dataset of car listings and applies **data analysis, preprocessing, and machine learning techniques** to build predictive models.

The workflow includes:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Dashboard design
- Feature Engineering
- Model Training
- Model Evaluation
- Model Deployment with **Streamlit**

---

# 📂 Project Structure

```
car-price-analsis-prediction-models/
│
├── datasets/
│   ├── CarPricePrediction.csv
│   └── cars_analyzed.csv
│
├── notebooks/
│   └── analysis.ipynb
│   └── predictive modeling.ipynb
│
├── models/
│   │── model.pkl
│   └── encoder.pkl
│   └── scaler.pkl
|
├── reports and dashboard/
│   │── car price prediction dashboad.pbix
│   └── report.html
|

├── visualizations/
│   └── Average Mileage by Make.png
│   └── Average price by make.png
│   └── Average price per condition.png
│   └── Boxplot per condition category.png
│   └── Correlation across year,mileage and price.png
│   └── Mileage vs age.png
│   └── Mileage vs price.png
│   └── Most common makes & models.png
│   └── condition vs year.png
│   └── depreciation curve by make.png
│   └── distribution by age.png
│   └── distribution of car prices-boxplot.png
│   └── distribution of car prices.png
│   └── distribution of car year-histplot.png
│   └── heatmap-average price by make and condition.png
│   └── line trend with years.png
│   └── make by price.png
│   └── mileage analysis.png
│   └── mileage vs conditions.png
│   └── number of cars in each year.png
│   └── price by make + condition.png
│   └── scatterplot price vs year.png
│
├── requirements.txt
└── README.md
```

---

# 📊 Exploratory Data Analysis (EDA)

During the analysis phase, several insights were discovered:

- Relationship between **engine size and car price**
- Impact of **brand and model** on price
- Effect of **mileage and car age** on price
- Identification of **correlated features**

Visualization techniques used include:

- Heatmaps
- Distribution plots
- Scatter plots
- Correlation matrices

---

# ⚙️ Data Preprocessing

The following preprocessing steps were applied:

- Handling missing values
- Encoding categorical variables using **Label Encoding**
- Feature scaling using **StandardScaler**
- Feature selection based on correlation

---

# 🤖 Machine Learning Models Used

The following regression models were trained and evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

---

# 📈 Model Performance

| Model | R² Score | MAE | MSE | RMSE |
|------|------|------|------|-----|
| Linear Regression | 0.9482 | 857.9356 | 1048295. 103 | 1023.8628 |
| Decision Tree | 0.9976 | 138.9822 | 47868.075 | 218.7848 |
| Random Forest | 0.99918 | 94.7195 | 16515.150 | 128.5112 |
| XGBoost | 0.999177 | 95.5979 | 16666.068 | 129.0968 |

Random Forest Regressor performed exceptionally well on this dataset.

---

# 🌐 Streamlit Web App

The trained model is deployed using **Streamlit**, allowing users to input car features and get an estimated price instantly.

### Example Features Used

- Car Make
- Model
- Year
- Mileage
- Age
- Condition
- Mileage Segment
- Year Bracket
- Mileage per Year
- Usage Level
- Make Model

---

# 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/car-price-prediction.git
cd car-price-prediction
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit App

```bash
streamlit run app.py
```

---

application can be found at https://car-price-prediction-app-by-success.streamlit.app/

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Streamlit

---

# 📌 Future Improvements

- Use larger and more diverse datasets
- Perform hyperparameter tuning
- Add more feature engineering techniques

---

# 📜 License

This project is open-source and available under the **MIT License**.

---

# 👨‍💻 Author

**Umazayi Success**

- Data Analyst / Data Scientist
- Passionate about machine learning and data-driven solutions
