# 📊 Placement Data Analysis Project

This project uses the **Placement.csv** dataset to analyze factors that affect student placements.  
The dataset provides detailed information on students’ academic performance, work experience, and placement outcomes.  

---

## 📁 Dataset Information

The dataset contains records of students including demographics, educational details, and placement status.  

### 🔑 Features

| Column Name      | Type    | Description                                                  |
| ---------------- | ------- | ------------------------------------------------------------ |
| `sl_no`          | int64   | Serial number (unique ID for each student)                   |
| `gender`         | int64   | Gender (encoded numerically, e.g., 0/1)                      |
| `ssc_p`          | float64 | Secondary Education percentage (10th grade)                  |
| `ssc_b`          | object  | Board of Secondary Education (Central/Others)                |
| `hsc_p`          | float64 | Higher Secondary Education percentage (12th grade)           |
| `hsc_b`          | object  | Board of Higher Secondary Education (Central/Others)         |
| `hsc_s`          | object  | Specialization in Higher Secondary (Commerce, Science, Arts) |
| `degree_p`       | float64 | Degree percentage (Bachelor’s level)                         |
| `degree_t`       | object  | Type of Degree (Sci&Tech, Comm&Mgmt, Others)                 |
| `workex`         | object  | Work experience (Yes/No)                                     |
| `etest_p`        | float64 | Employability test percentage                                |
| `specialisation` | object  | MBA Specialisation (Mkt&Fin, Mkt&HR)                         |
| `mba_p`          | float64 | MBA percentage                                               |
| `status`         | object  | Placement status (Placed/Not Placed)                         |
| `salary`         | float64 | Salary offered (in INR) – missing for not placed students    |

---

## 🎯 Project Objectives

1. Perform **Exploratory Data Analysis (EDA)** to understand trends and correlations.  
2. Analyze the impact of academic scores, degree type, and work experience on placements.  
3. Build **predictive models** (Logistic Regression, Decision Trees, etc.) to classify placement status.  
4. Visualize the insights using **Matplotlib** and **Seaborn**.  

---

## ⚙️ Technologies Used

- **Python 3**  
- **NumPy** – numerical computing  
- **Pandas** – data manipulation  
- **Matplotlib / Seaborn** – data visualization  
- **Scikit-learn** – machine learning models  

## A few points to note:-

The dataset used in the project has been provided for reference: Jain University Bangalore Campus Placement Dataset- **Placement.csv** Contains 215 student records Includes secondary and higher secondary school percentages and specialization Also includes degree specialization, type and work experience, and salary offers to the placed students Placed (label = 1) Not Placed (label = 0) 90/10 train/test split

Our model may not achieve the best accuracy(fiddling with the various parameters may enhance it)