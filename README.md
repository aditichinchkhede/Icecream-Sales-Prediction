# 🍦 Ice Cream Sales Prediction using Polynomial Regression

## 📌 Overview
This project explores the relationship between temperature and ice cream sales using Machine Learning. It uses **Polynomial Regression (Degree 4)** to model the relationship between temperature and ice cream sales, visualizing how sales vary with temperature.

## 🎯 Objective
To analyze temperature-based ice cream sales data and fit a polynomial regression model that captures the relationship between temperature and sales.

## 📊 Dataset
The dataset contains two main variables:

- **Temperature (°C)**: The input feature
- **Ice Cream Sales (units)**: The target variable

Dataset file: `Ice_cream_selling_data.csv`

## 🛠️ Technologies & Libraries Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## ⚙️ Project Workflow
1. Import the required libraries.
2. Load the dataset using Pandas.
3. Visualize the relationship between temperature and ice cream sales using a scatter plot.
4. Extract the input feature (X) and target variable (y).
5. Transform the input data using `PolynomialFeatures` with degree 4.
6. Train a Linear Regression model on the transformed data.
7. Evaluate the model using the R² score.
8. Visualize the fitted polynomial regression curve.

## 📈 Model
- **Algorithm:** Polynomial Regression
- **Polynomial Degree:** 4
- **Base Estimator:** Linear Regression
- **Evaluation Metric:** R² Score

Polynomial regression allows the model to capture nonlinear patterns in the data by adding polynomial features.

## 📉 Visualizations
The project includes:
- A scatter plot showing temperature vs. ice cream sales.
- A polynomial regression curve fitted to the dataset.

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/your-username/ice-cream-sales-prediction.git
```

### 2. Navigate to the project directory
```bash
cd ice-cream-sales-prediction
```

### 3. Install dependencies
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### 4. Add the dataset
Make sure `Ice_cream_selling_data.csv` is placed in the project folder.

### 5. Run the project
```bash
python test.py
```

## 📂 Project Structure
```text
ice-cream-sales-prediction/
│
├── test.py
├── Ice_cream_selling_data.csv
└── README.md
```

## 📌 Results
The model fits a degree-4 polynomial curve to the observed temperature and ice cream sales data. The R² score is calculated to evaluate how well the model fits the dataset.

## 👩‍💻 Author
**Your Name**

---

*This project was created for learning and exploring Polynomial Regression in Machine Learning.*
