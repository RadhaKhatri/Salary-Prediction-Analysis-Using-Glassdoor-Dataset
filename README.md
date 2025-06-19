# Salary-Prediction-Analysis-Using-Glassdoor-Dataset
Salary Prediction &amp; Analysis Using Glassdoor Dataset

# 💼 Tech Salary Prediction using Glassdoor Job Postings (2017–2018)

## 📌 Project Overview

In today’s rapidly evolving tech industry, understanding salary trends is essential for job seekers, employers, analysts, and policymakers. This project leverages a dataset from [Glassdoor.com](https://www.glassdoor.com) (2017–2018) to build predictive models that estimate salaries based on various job-related features such as job title, company size, and location.

We apply machine learning techniques to predict salaries, visualize compensation trends, and derive valuable insights for decision-making.

---

## 🧠 Business Objectives

- **Job Seekers**: Make better career decisions by understanding expected salary ranges.
- **Employers**: Set competitive salaries to attract and retain talent.
- **Analysts & Researchers**: Discover patterns across geography, job roles, and industries.
- **Recruiters**: Benchmark salaries and improve compensation practices.

---

## ❓ Problem Statement

- How does salary vary by **job role** (e.g., Data Scientist vs. DevOps Engineer)?
- How does **company size** impact salary?
- What is the salary difference between **locations** (e.g., Austin vs. NYC)?
- Can we build a **predictive model** to estimate salaries based on job attributes?

---

## 🧾 Dataset Description

The dataset contains job postings scraped from **Glassdoor.com** between 2017 and 2018. Key features include:
- `job_title`, `salary_estimate`, `company_name`, `location`, `industry`, `company_size`, `rating`, `revenue`, etc.
- Also includes derived features like `avg_salary`, `hourly`, `employer_provided`, etc.

---

## 🧰 Libraries & Tools Used

- 🐼 **Pandas** – data manipulation and cleaning
- 📊 **Matplotlib & Seaborn** – visualization
- 🧮 **NumPy** – efficient numeric operations
- 🤖 **Scikit-learn** – machine learning models (Linear Regression, Decision Tree, Random Forest)
- 🖼 **Tkinter** – GUI development for local use

---

## 🧪 Model Evaluation

| Model              | MAE (Mean Absolute Error) |
|-------------------|---------------------------|
| Linear Regression | 0.0000876                 |
| Random Forest     | 0.7377                    |
| Decision Tree     | 0.9497                    |

✅ Best model: **Linear Regression**

---

## 📈 Visualizations Created

- 💼 Average Salary by Job Title
- 🌍 Salary Distribution by Location
- 🏢 Salary vs. Company Size
- 🔥 Feature Correlation Heatmap
- 📊 Box Plots for Salary by Industry

---

## 🖥 GUI – Salary Predictor

A desktop GUI using **Tkinter** allows users to enter job title, location, and company size to predict an estimated salary using the trained model.

---

## 📊 Project Architecture

[Project Structure Understanding] → [Data Analysis & Preprocessing] → [Model Building] → [Evaluation] → [Visualizations] → [GUI Deployment]


---

## 🚀 How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/tech-salary-predictor.git
cd tech-salary-predictor

2. Install Dependencies
pip install -r requirements.txt

3. Train the Model (if not already trained)
python model_training.py

4. Launch GUI


📚 Future Improvements
Deploy the model using Streamlit or Flask as a web application

Integrate more recent datasets for up-to-date salary prediction

Add resume parsing and automatic salary suggestion features







