# Customer Churn Analysis 

This project focuses on analyzing customer churn to understand the patterns and reasons behind customer attrition, and provide data-driven insights to help improve customer retention strategies.

## 📌 Objective

The goal of this project is to:

- Identify key factors that lead to customer churn.
- Visualize churn trends and customer behaviors.
- Build a predictive model to classify customers as likely to churn or not.

## 📊 Dataset

The dataset contains customer information such as:

- Demographics (gender, age group, etc.)
- Services subscribed (internet, phone, streaming)
- Payment methods
- Tenure and monthly charges
- Churn status (Yes/No)

> Note: The dataset used is a sample telecom customer dataset.

## 🧠 Process

1. **Data Cleaning** – Handled missing values and data types.
2. **Exploratory Data Analysis (EDA)** – Used visualizations to explore relationships between features and churn.
3. **Feature Engineering** – Transformed and selected relevant features.
4. **Model Building** – Trained classification models to predict churn.
5. **Evaluation** – Measured model accuracy and performance.

## 📈 Results

- The Random Forest model achieved higher accuracy and recall compared to Logistic Regression.
- Key indicators of churn include contract type, tenure, monthly charges, and the presence of tech support.

## 🧰 Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## ⚙️ How to Run

1. Clone the repository:
   git clone https://github.com/your-username/your-repo-name.git

2. Navigate to the project folder:
   cd your-repo-name

3. (Optional) Create a virtual environment:
   python -m venv venv
   
   # On Windows, use the following command to activate:
   venv\Scripts\activate
   
   # On macOS/Linux, use:
   source venv/bin/activate

4. Install required libraries:
   pip install -r requirements.txt

5. Run the notebook:
   jupyter notebook Customer_Churn_.ipynb


