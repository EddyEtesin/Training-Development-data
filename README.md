# 📚 Training & Development Data Analysis with Pandas

This project explores a corporate training dataset to evaluate the effectiveness and efficiency of various training programs over time. Using Python’s **Pandas**, **Matplotlib**, and **Seaborn**, this notebook delivers insights into training completion rates, cost-efficiency, and overall performance metrics to support HR and organizational development decisions.

---

## 📁 Dataset Overview

The dataset (`training_and_development_data.csv`) includes records of employee training programs with fields such as:

- `Employee ID`
- `Department`
- `Training Program`
- `Training Date`
- `Training Outcome`
- `Cost of Training`

---

## 🎯 Analytical Goals

- 📈 **Quarterly Completion Trends**  
  Track changes in completion rate over time by resampling data quarterly

- 💸 **Cost Efficiency**  
  Identify programs with the best **cost per successful completion**

- 🏅 **Top Performing Departments**  
  Analyze which departments consistently complete their training programs

- ⚖️ **Training Outcome Distribution**  
  Visualize completion vs non-completion rates

---

## 🛠️ Tools Used

- `pandas` for data manipulation and time series resampling  
- `numpy` for numerical operations  
- `matplotlib` & `seaborn` for data visualization  
- `datetime` for handling and converting training dates  

---

## 🧠 Skills Demonstrated

- Data Cleaning & Type Conversion (`datetime`, categorical fields)  
- Time Series Resampling (quarterly grouping)  
- Custom KPI Calculation (e.g., cost per successful completion)  
- Visual Storytelling with Charts and Plots  

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/training-data-analysis.git
   cd training-data-analysis
