# Job-Market-Analysis-Using-EDA-Machine-Learning
# Exploratory Job Market Analysis & Salary Prediction

## 📌 Project Overview
This project performs an end-to-end exploratory analysis of job market data to uncover hiring trends, in-demand skills, salary patterns, and builds a machine learning model to predict salaries based on experience, role, and skill requirements.

The project combines **EDA + feature engineering + regression modeling** to simulate a real-world data analytics workflow.

---

## 📂 Dataset Information
- **Records:** 250 job postings
- **Features:** 10 columns including job title, salary range, experience, location, and skills
- **Domain:** Job Market / Hiring Analytics

---

## 🛠️ Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

## 🔍 Key Analysis Performed

### 1. Exploratory Data Analysis
- Job role distribution
- Job type and location trends
- Salary range analysis
- Experience vs salary relationship

### 2. Skill Demand Analysis
- Extracted skills from text data
- Identified top in-demand tools and technologies
- Observed preference for practical, industry-ready skills

### 3. Feature Engineering
- Average salary computation
- Skill count extraction
- Label encoding for categorical features

### 4. Machine Learning Model
- Built a Linear Regression model to predict salary
- Features used:
  - Experience required
  - Skill count
  - Job role
  - Job type
- Model evaluated using R² score and MAE

---

## 📊 Key Insights
- Engineering and Machine Learning roles dominate the market
- Experience is the strongest predictor of salary
- Skill diversity significantly influences compensation
- Git, Docker, AWS, Agile, and Python are the most demanded skills
- Remote and full-time jobs offer higher average salaries

---

## 🚀 How to Run the Project
1. Clone the repository
2. Upload `job_market.csv` to Google Colab or local environment
3. Run the notebook or Python script step-by-step
4. Visualizations and results will be generated automatically

---

## 📌 Future Improvements
- Skill encoding using TF-IDF
- Tree-based models (Random Forest, XGBoost)
- Location-based salary normalization
- Interactive dashboard using Plotly or Power BI

---

## 🧠 Learning Outcome
This project demonstrates how data analysis and machine learning can be applied to real-world hiring data to support career insights, salary benchmarking, and skill planning.
