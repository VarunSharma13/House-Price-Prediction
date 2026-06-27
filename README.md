# 🏡 House Price Prediction using Machine Learning

A machine learning project that predicts house prices using the California Housing dataset. This project demonstrates a complete end-to-end ML workflow, including data exploration, preprocessing, model training, hyperparameter tuning, evaluation, and prediction.

---

## 📌 Project Overview

This notebook follows a structured machine learning pipeline:

- Data Loading
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Engineering
- Model Training
- Cross-Validation
- Hyperparameter Tuning using GridSearchCV
- Model Evaluation
- House Price Prediction

The goal is to build a regression model capable of accurately estimating house prices based on various housing features.

---

## 📂 Project Structure

```
House-Price-Prediction/
│
├── house price prediction.ipynb   # Main notebook
├── housing.csv                    # Dataset
├── README.md                      # Project documentation
└── requirements.txt               # Python dependencies (optional)
```

---

## 📊 Dataset

The project uses the **California Housing Dataset** (`housing.csv`).

### Features

- Longitude
- Latitude
- Housing Median Age
- Total Rooms
- Total Bedrooms
- Population
- Households
- Median Income
- Ocean Proximity

### Target Variable

- Median House Value

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🚀 Machine Learning Workflow

### 1. Data Loading

- Import dataset
- Inspect data
- Check missing values

### 2. Exploratory Data Analysis

- Dataset overview
- Statistical summary
- Feature distributions
- Correlation analysis
- Data visualization

### 3. Data Preprocessing

- Missing value handling
- Feature scaling
- Categorical feature encoding
- Train-test split

### 4. Model Building

The notebook builds regression models using Scikit-learn pipelines and evaluates them with cross-validation.

### 5. Hyperparameter Tuning

- GridSearchCV
- Cross-validation
- Best parameter selection

### 6. Model Evaluation

Performance is evaluated using common regression metrics such as:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/House-Price-Prediction.git
```

Move into the project directory:

```bash
cd House-Price-Prediction
```

Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
house price prediction.ipynb
```

Run all cells sequentially.

---

## 📈 Results

The project compares different regression models and selects the best-performing model using cross-validation and hyperparameter tuning.

The final model can be used to predict house prices for unseen housing data.

---

## 📷 Sample Workflow

```
Load Dataset
      │
      ▼
Explore Data
      │
      ▼
Preprocess Data
      │
      ▼
Train Models
      │
      ▼
Cross Validation
      │
      ▼
Grid Search
      │
      ▼
Best Model
      │
      ▼
Evaluate
      │
      ▼
Predict House Prices
```

---

## 💡 Future Improvements

- Try XGBoost or LightGBM
- Feature selection techniques
- Model deployment with Flask or FastAPI
- Interactive web application using Streamlit
- Docker support
- CI/CD integration

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## 👨‍💻 Author

**Varun**

If you found this project useful, consider giving it a ⭐ on GitHub.
