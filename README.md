# Telecom-churn-analysis
## 📌 Project Description

This project aims to predict customer churn in a telecom company using machine learning techniques. The model helps identify customers who are likely to leave the service so that proactive retention strategies can be implemented.

The dataset includes various features such as tenure, monthly charges, contract type, and services subscribed. The project includes data preprocessing, exploratory data analysis, model training, and evaluation using classification metrics.

## 🧑‍💻 Who Are the End Users?

- Telecom Customer Retention Teams
- Marketing & Strategy Teams
- Customer Service Representatives
- Data Science & Analytics Teams

## 💡 Problem Statement

Customer churn negatively impacts telecom companies' revenue and stability. Predicting churn enables data-driven decision-making for customer retention and personalized offers.

## 🛠️ Technologies Used

- **Language**: Python
- **Tools**: Jupyter Notebook
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn

## 📊 Results

- The best performing model: Random Forest Classifier
- Key metrics (example):
  - Accuracy: ~82%
  - Precision: ~78%
  - Recall: ~77%
  - F1 Score: ~77%
- Insights:
  - Customers with higher monthly charges are more likely to churn.
  - Longer tenure reduces the likelihood of churn.
  - Fiber optic internet users and customers without tech support are more likely to leave.

## 🗃️ Files in This Repository

- Telecom_Churn_Case_Study.ipynb: The main Jupyter Notebook with code and visualizations.
- telecom_churn.csv: The dataset used.
- README.md: This file.
- ## 🚀 How to Run Locally in Jupyter Notebook

Follow the steps below to run this project on your local machine using Jupyter Notebook:

### 1. Clone the Repository


git clone https://github.com/yourusername/telecom-churn-prediction.git
cd telecom-churn-prediction


> Replace `yourusername` with your actual GitHub username.

### 2. (Optional) Create and Activate a Virtual Environment

It's a good practice to isolate dependencies using a virtual environment.

**For Windows:**


python -m venv venv
venv\Scripts\activate


**For macOS/Linux:**


python3 -m venv venv
source venv/bin/activate


### 3. Install Required Libraries

Install all necessary packages using pip:


pip install pandas numpy matplotlib seaborn scikit-learn


### 4. Launch Jupyter Notebook

Start Jupyter Notebook in your browser:


jupyter notebook


### 5. Open and Run the Notebook

- In the Jupyter dashboard, open `Telecom_Churn_Case_Study.ipynb`
- Make sure the file `telecom chrn.csv` is present in the same directory
- Run each cell in order to:
  - Load and preprocess the dataset
  - Perform Exploratory Data Analysis (EDA)
  - Train and evaluate machine learning models
  - Review performance metrics and insights

### ✅ Output

After running the notebook, you will get:
- A trained churn prediction model
- Visual insights into churn patterns
- Evaluation metrics like accuracy, precision, recall, and F1 score

> Ensure Python 3.x and Jupyter are properly installed before beginning.
