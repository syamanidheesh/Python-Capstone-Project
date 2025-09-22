# ABC Company Employee Data Analysis

## Project Overview
This project presents a complete analysis of the employee dataset from **ABC Company**. The dataset consists of **458 rows** and **9 attributes**, covering workforce details, salary trends, and other insights.  

The project involves:
- Data preprocessing  
- Data analysis
- Graphical visualizations  
- Key insights and conclusions  

---

## Dataset Description
**File:** `ABC Company.xlsx`  

- **Rows:** 458  
- **Columns:** 9  

| Attribute | Description |
|-----------|-------------|
| Name      | Name of the employee |
| Team      | Team in which employee works |
| Number    | Employee number |
| Position  | Designation or role of the employee |
| Age       | Employee’s age |
| Height    | Employee’s height |
| Weight    | Employee’s weight |
| College   | College attended by the employee |
| Salary    | Annual salary of the employee |

---

## 1. Preprocessing

### Cleaning
- Checked for **missing values**.  
- Columns with missing data: **College** and **Salary**.  
- Missing values were filled using `fillna()` with the **forward fill method**.

### Organizing
- The `Height` column contained **erroneous text values** and inconsistent entries.  
- Replaced invalid values with **random numeric values between 150–180 cm**.  

---

## 2. Analysis & Visualizations

### 2.1 Employee Distribution Across Teams
- **Total number of employees** in each team was calculated and the percentage split of the total employees also find out.
- **Visualization:** Seaborn **Barplot**  



### 2.2 Employee Segregation by Position
- Grouped employees by their **position**.  
- **Visualization:** **Pie Chart**  



### 2.3 Predominant Age Group
- Split employees into **age groups**.  
- Identified the most **predominant age group**.  
- **Visualization:** Seaborn **Barplot** & **Histogram**  



### 2.4 Team and Position with Highest Salary Expenditure
- Calculated **total salary expenditure per team and position** and identified the **highest spending team and position**.  
- **Visualization:** **Barplot**  



### 2.5 Correlation Between Age and Salary
- Analyzed correlation between **employee age and salary**.  
- **Visualization:** **Scatterplot**  

---

## 3. Key Insights & Conclusions
- Employees are evenly spread across **30 teams**.  
- Majority of employees are **under 30 years old**, indicating a focus on hiring young talent.  
- The **SF** position in **Los Angeles Lakers** has the **highest salary expenditure**.  
- There is a moderate relationship between Age and Salary — **middle-aged employees earn higher salaries** compared to younger ones.  


