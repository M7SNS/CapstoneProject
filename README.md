# 🧠 Medical Insurance Cost Analysis (Capstone Project)

## 📌 Overview
This project focuses on analyzing a medical insurance dataset to understand the factors that influence insurance charges. The goal is to explore relationships between features such as age, BMI, smoking status, and other variables, and determine how they impact medical costs.

Through data cleaning, visualization, and statistical analysis, this project aims to extract meaningful insights and support data-driven conclusions.

---

## 🎯 Objectives
The main questions explored in this project:

- Which factors influence medical insurance charges?
- Which factor has the strongest impact on charges?
- Can we estimate health risk based on available data?

---

## 📊 Dataset
The dataset contains information about individuals including:

- Age  
- BMI (Body Mass Index)  
- Number of children  
- Smoking status  
- Insurance charges  

---

## ⚙️ Project Workflow

### 1. Data Cleaning
- Checked for missing values  
- Converted categorical data into numerical format  
- Ensured data consistency  

### 2. Feature Engineering
- Created new features such as:
  - charges_per_child
  - risk_score
  - age_bmi_interaction

### 3. Exploratory Data Analysis (EDA)
- Distribution analysis (age, BMI, charges)  
- Correlation analysis between variables  
- Visualization using histograms and plots  

### 4. Statistical Analysis
- Mean and standard deviation calculations  
- Feature scaling (StandardScaler)  
- Similarity analysis (cosine similarity)  

### 5. Insights
- Smoking status has a strong effect on charges  
- BMI and age show moderate relationships  
- Data is well distributed across age groups  

---

## 🧪 Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## 🚀 How to Run

1. Clone the repository:
git clone https://github.com/M7SNS/CapstoneProject.git

2. Navigate to the project folder:
cd CapstoneProject

3. Install dependencies:
pip install pandas numpy matplotlib scikit-learn

4. Run the notebook:
jupyter notebook

---

## 📈 Key Findings
- Smokers tend to have significantly higher insurance charges  
- No strong redundancy between features  
- Engineered features improved understanding of risk patterns  

---

## 🔮 Future Work
- Build predictive models  
- Improve feature engineering  
- Add evaluation metrics  
- Deploy as a web app  

---

## 👤 Author
M7SNS

---

## 📄 License
This project is for educational purposes.
