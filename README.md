# Housing Price Prediction

A project to predict house prices using machine learning techniques.
The project is built on the housing.csv dataset and presents the complete steps from data exploration to model building and evaluation.

---

##  Repo Contents
- `housing.csv`: House price data.
- `notebook.ipynb`: The main notebook containing all project steps.

---

##  Project Steps

### 1. Exploration Data (EDA)
- Examine the shape and columns of the data.
- Deal with missing values ​​(remove them because they are small).
- Analyze data distributions and plot graphs such as the distribution of house prices.
- Create a Correlation Heatmap to understand the relationship between characteristics and the target price.

### 2. Data Preprocessing
- Split the data into **Features (X)** and **Target (y)**.
- Separate the numeric columns from the categorical column `ocean_proximity`.
- Perform **Scaling** for the numeric columns and **One-Hot Encoding** for the categorical column.
- Create a **ColumnTransformer** that automatically prepares the data before training.

### 3. Data Splitting
- We split the data into **Training (80%) and **Testing (20%) using `train_test_split`.

### 4. Models Used
- **Linear Regression**: As a baseline model.
- **Random Forest Regressor**: To improve accuracy and the ability to capture complex relationships.

### 5. Evaluation
- We used **Mean Squared Error (MSE)** and **R² Score** to evaluate the models. We compared the results between Linear Regression and Random Forest to determine which is better.

---

##  Results
- The **Linear Regression** model gave reasonable results as a starting point.
- The **Random Forest** model performed better and achieved higher accuracy on the test data.

---

##  Notes
- The results can be further improved by experimenting with other algorithms or performing **Hyperparameter Tuning**.
- The model can be saved as `.joblib` for reuse in other applications (such as the Streamlit interface).

---

##  Tools Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Linear Regression, Random Forest, Pipelines)

---

##  Project Objective
Learn the steps for building a complete ML project:
1. Understand and explore data.
2. Data cleaning and preparation.
3. Training different ML models.
4. Evaluating and comparing results.

This project is a practical introduction to applying machine learning to real data.
