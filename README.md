# 📊 NGO Impact Measurement Dashboard

> **Transforming Raw Field Data into Actionable Social Impact Insights**

An end-to-end Business Intelligence project that enables NGOs to measure program effectiveness, evaluate beneficiary outcomes, monitor resource utilization, and support evidence-based decision-making through an interactive Power BI dashboard.

The project integrates data cleaning, feature engineering, exploratory data analysis (EDA), KPI development, and dashboard visualization to convert raw beneficiary data into meaningful impact metrics.

---

# 📌 Table of Contents

- Project Overview
- Problem Statement
- Objectives
- Solution Workflow
- Repository Structure
- Dataset
- Technologies Used
- Data Preparation
- Exploratory Data Analysis
- Dashboard Design
- KPI Framework
- Key Insights
- Dashboard Features
- Business Impact
- Future Enhancements
- Usage
- Author

---

# 📖 Project Overview

Many NGOs successfully track operational activities such as beneficiary enrollment, attendance, and program delivery. However, measuring the actual social impact of these activities remains a significant challenge.

This project addresses that gap by developing an interactive NGO Impact Measurement Dashboard that transforms beneficiary-level data into actionable insights, helping organizations evaluate learning outcomes, compare program performance, optimize resource allocation, and improve accountability.

---

# 🎯 Problem Statement

Traditional NGO reporting focuses on activities rather than outcomes, making it difficult to answer critical questions such as:

- Did beneficiaries actually improve?
- Which programs create the greatest impact?
- Are financial resources being utilized efficiently?
- Which interventions deserve additional investment?
- How can program effectiveness be measured objectively?

This project shifts the focus from activity tracking to measurable social impact.

---

# 🚀 Objectives

- Measure program effectiveness
- Monitor beneficiary reach
- Evaluate learning outcomes
- Improve cost efficiency
- Track completion rates
- Compare program performance
- Build an interactive decision-support dashboard
- Enable evidence-based resource allocation

---

# 🏗 Solution Workflow

```text
Raw NGO Dataset
        │
        ▼
Data Cleaning & Validation
        │
        ▼
Feature Engineering
        │
        ▼
Exploratory Data Analysis
        │
        ▼
KPI Development
        │
        ▼
Interactive Power BI Dashboard
        │
        ▼
Actionable Insights
        │
        ▼
Better Decision Making
```

---

# 📂 Repository Structure

```text
NGO-Impact-Measurement-Dashboard/
│
├── README.md
├── data/
├── notebooks/
├── dashboard/
├── docs/
├── outputs/
└── assets/
```

---

# 📊 Dataset Overview

The project uses a beneficiary-level dataset representing NGO educational programs.

### Dataset Summary

- Total Beneficiaries: **300**
- Districts Covered: **5**
- Programs: **4**
- Gender Categories: **Male & Female**
- Records Analysed: **300**

### Key Variables

- Student ID
- Gender
- Age
- District
- Program Name
- Attendance Percentage
- Attendance Bin
- Pre-Test Score
- Post-Test Score
- Improvement Percentage
- Program Cost
- Completion Status
- Outcome Achieved
- Enrollment Date

---

# 💻 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Power BI
- Jupyter Notebook

---

# 🧹 Data Preparation

The dataset was prepared through:

- Missing value treatment
- Duplicate removal
- Data validation
- Feature engineering
- KPI calculation
- Business rule validation

### Missing Value Treatment

| Variable | Method |
|-----------|---------|
| Gender | Mode |
| District | Mode |
| Post-Test Score | Median |

---

# ⚙ Feature Engineering

The following analytical metrics were created:

### Improvement Percentage

Measures learning gain between pre-test and post-test scores.

### Attendance Bins

- 25–50%
- 50–75%
- 75–100%

### Completion Status

- Yes
- No

### Outcome Achievement

- Yes
- No

---

# 📈 Exploratory Data Analysis

EDA was performed to answer important business questions:

- Does attendance improve learning outcomes?
- Which NGO program performs best?
- Which attendance group achieves the highest success?
- What is the relationship between cost and impact?
- Which programs generate measurable outcomes?

---

# 📊 Dashboard Features

The dashboard provides:

### KPI Cards

- Total Students
- Total Program Cost
- Completion Rate
- Outcome Achievement Rate
- Average Improvement
- Cost Per Successful Student

### Interactive Filters

- Gender
- District
- Program Name

### Visualizations

- Attendance vs Learning Improvement
- Average Improvement by Program
- Outcome Achievement Distribution
- Attendance Bin vs Outcome Achievement
- KPI Impact Framework

---

# 📌 Key Performance Indicators

| KPI | Value |
|------|-------|
| Total Students | 300 |
| Total Program Cost | ₹503.8K |
| Completion Rate | 48.67% |
| Outcome Achievement Rate | 60.33% |
| Average Improvement | 30.95% |
| Cost per Successful Student | ₹2.78K |

---

# 🔍 Key Insights

### 1. Attendance Drives Learning

Students with higher attendance consistently achieved better learning improvements.

---

### 2. Scholarship Support Performs Best

Scholarship Support recorded the highest average improvement among all NGO programs.

---

### 3. Outcome Achievement

More than **60%** of beneficiaries successfully achieved the desired learning outcome.

---

### 4. Cost Efficiency

The NGO spends approximately **₹2,780** for every successfully impacted beneficiary.

---

### 5. Dashboard KPI

Outcome Achievement Rate was identified as the most important executive KPI for weekly performance review.

---

# 🌍 Business Impact

The dashboard enables NGOs to:

- Measure program effectiveness
- Evaluate beneficiary outcomes
- Improve funding transparency
- Optimize resource allocation
- Support donor reporting
- Monitor cost efficiency
- Strengthen accountability
- Make evidence-based decisions

---

# 🚀 Future Enhancements

- Automated data refresh
- Mobile dashboard
- Real-time beneficiary tracking
- Predictive analytics
- AI-powered impact forecasting
- Donor reporting automation
- Multi-NGO deployment

---

# 📁 Documentation

The repository includes:

- Presentation Deck
- Dashboard User Guide
- Data Dictionary
- Power BI Dashboard Template

---

# 👨‍💻 Author

**Harsh Rishi**

B.Tech Civil Engineering  
Indian Institute of Technology Roorkee

---

⭐ If you found this project useful, consider giving the repository a Star.
