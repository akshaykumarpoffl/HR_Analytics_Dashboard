# HR Analytics Dashboard

## 📌 Project Overview

This project is an **HR Analytics Dashboard** built using **Power BI** to analyze employee attrition trends. The dashboard provides insights into factors such as attrition by age, job role, salary, education, and more. It aims to help HR professionals identify patterns and take proactive measures to reduce attrition.

## 📊 Dataset Information

- The dataset used in this project is **publicly available**.
- It contains information about employees, including **age, salary, job role, years at the company, education background, and attrition status**.
- The dataset was pre-processed in **Power Query** before visualization.

## 🔍 Data Cleaning & Preprocessing

The following steps were performed to clean and prepare the data for analysis:

- **Removed an inappropriate column.**
- **Removed duplicate values to ensure data accuracy.**
- **Replaced missing or incorrect values**.
- **Changed data types** where necessary.
- **Added an 'Attrition Count' column**:
  - The original dataset had an "Attrition" column with values **Yes/No**.
  - Converted this into **1 (Yes) and 0 (No)** for numerical analysis.

## 📈 Key Dashboard Insights

- **Total Employees:** 1470
- **Total Attrition:** 237
- **Attrition Rate:** 16.1%
- **Average Salary:** 6.5K
- **Average Years in Company:** 7.0
- **Attrition breakdown by:**
  - **Age Groups** (Most attrition occurs in the 26-35 age range)
  - **Job Roles** (Laboratory Technicians have the highest attrition)
  - **Gender** (Male attrition is higher)
  - **Salary Slabs** (Lower salary groups have higher attrition)
- **Department-wise Analysis using Slicers:**
  - A slicer allows users to filter the dashboard by **Human Resources, Research & Development, and Sales** departments.
  - This enables targeted analysis of attrition trends within each department.

## 🛠 How to Use This Repository

This repository includes the following files:

### 📂 File Structure

```
📂 HR_Analytics_Dashboard
├── 📂 Data
│   ├── raw_data.csv         # Original dataset
│   ├── cleaned_data.csv     # Preprocessed dataset
├── 📂 Report_Preview
│   ├── HR_Analytics_Dashboard.pdf  # Exported dashboard in PDF format
├── HR_Analytics_Dashboard.pbix  # Power BI file (without data)
├── README.md
```

### 🔹 Using the PBIX File

Since the **Power BI (.pbix) file** does not contain the dataset, users can:

1. **Download the cleaned dataset (********`cleaned_data.csv`************\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*********\*\*\*\*\*\*\*\*)**\*\*\*\*\*\*\*\*\*.csv)\*\*.
2. **Open the ************************************************************************`HR_Analytics_Dashboard.pbix`************************************************************************ file in Power BI**.
3. **Load the cleaned dataset into Power BI** to see the dashboard with full functionality.
4. **Use the department slicer** to filter the dashboard by **Human Resources, Research & Development, and Sales** to analyze attrition within specific departments.

## ⚖️ License & Acknowledgment

- This project is based on a **publicly available dataset**.
- No direct attribution is provided to the original source as per the user's preference.
- Feel free to use or modify the project as needed.

---

If you find this project useful, feel free to ⭐ the repository!

Happy analyzing! 🚀

