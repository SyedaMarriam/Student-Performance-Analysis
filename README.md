# 🎓 Student Performance Analysis Project

[![Python Version](https://shields.io)](https://python.org)
[![Pandas](https://shields.io)](https://pydata.org)
[![Jupyter](https://shields.io)](https://jupyter.org)

A comprehensive Data Manipulation and Exploratory Data Analysis (EDA) project focused on analyzing student academic records, evaluating performance trends, and generating insightful data visualizations.

## 📌 Project Overview
The primary goal of this project is to clean, manipulate, and analyze a dataset containing student academic information. By processing metrics like GPA, marks, attendance, and demographics, this project extracts actionable insights to understand student performance patterns and identify factors contributing to academic success.

### Key Objectives
* Clean raw student data by handling missing values and eliminating duplicate records.
* Perform descriptive statistical analysis on marks and GPA distributions.
* Segment student data based on Gender, Academic Program, and City.
* Identify top performers and students requiring urgent academic attention.
* Conduct Pass/Fail analysis and program-wise performance comparisons.
* Generate high-quality visual charts for intuitive reporting.


## 📂 Project Structure
The repository is structured systematically to separate the data manipulation phase from the visualization assets:

STUDENT PROJECT/
│
├── 📂 Data Manipulation/
│   ├── 📄 Data_Analysis.ipynb     # Jupyter Notebook for data cleaning & EDA
│   └── 📊 Student_data.xlsx       # Raw excel dataset
│
├── 📂 Data Visualization/
│   ├── 🖼️ Attendance Distribution.png
│   ├── 🖼️ Attendance vs Obtained Marks.png
│   ├── 🖼️ Average Marks by Program and Year.png
│   ├── 📄 Charts.ipynb            # Jupyter Notebook for generating visualizations
│   ├── 🖼️ Gender Distribution.png
│   ├── 🖼️ Grade Distribution.png
│   ├── 🖼️ Result Ratio.png
│   ├── 📊 Student_data.xlsx       # Reference copy of the dataset
│   └── 🖼️ Students by Program.png
│
└── 📋 README.md                   # Project documentation
```

---

## Tools & Technologies Used
* **Python** 🐍 – Core programming language.
* **Pandas** – Data manipulation and structured analysis.
* **NumPy** – Numerical and array computing.
* **Matplotlib & Seaborn** – Data visualization and statistical plotting.
* **Jupyter Notebook** – Interactive development and documentation workspace.

---

## 📊 Core Analysis Pipeline

### 1. Data Preprocessing & Cleaning
* **Inspection:** Initial data structural checks using `.head()`, `.tail()`, and `.info()`.
* **Deduplication:** Identified and eliminated duplicate entries using `.duplicated()` to secure data unique integrity.
* **Imputation:** Filtered and addressed missing/null data fields with `.isnull().sum()`.

### 2. Exploratory Data Analysis (EDA)
* **Descriptive Statistics:** Generated overall summaries (Mean, Median, Min, Max) using `.describe()`.
* **Demographics Breakdown:** Computed metrics tracking Total Students, Gender Distribution, and City-wise student counts.
* **Academic Enrolment:** Visualized program strength by grouping records per academic stream.

### 3. Advanced Insights
* **Top Performers:** Isolated high-achieving students via advanced sorting and conditional filtering.
* **At-Risk Monitoring:** Filtered profiles with critically low marks to flag students requiring academic assistance.
* **Performance Ratios:** Calculated overall Pass/Fail margins and calculated mean/median GPAs horizontally across different university programs.

---

## 📈 Key Visualizations Generated
The visual files saved in the `Data Visualization/` directory provide graphical evidence for the analysis:
* **Attendance Distribution:** Evaluates student regularities.
* **Attendance vs Obtained Marks:** Explores the correlation between class attendance and final grades.
* **Average Marks by Program and Year:** Displays progress trends across multiple academic years.
* **Grade & Result Ratios:** Displays passing matrices and overall performance distribution.

---

## 🚀 How to Run the Project

### Prerequisites
Make sure you have Python installed, along with the required libraries. You can install them via terminal:
```bash
pip install pandas numpy matplotlib seaborn openpyxl jupyter
```

### Steps to Execute
1. Clone or download this project repository to your local machine.
2. Open VS code --> Click file --> Open folder and then select the folder(Student Performance Analysis) and open.
3. Navigate to `Data Manipulation/Data_Analysis.ipynb` and run all cells to see the data cleaning and pipeline steps.
4. Navigate to `Data Visualization/Charts.ipynb` and run all cells to regenerate or view the visualization plots.

---

### 👩‍💻 About the Developer
This project was developed as part of my learning journey in Python programming and data analysis.
It demonstrates practical application of programming concepts to solve a real-world record management problem.

### ⭐ Feedback
If you find this project useful, feel free to explore the code, share feedback, and suggest improvements.
Thank you for visiting my project!