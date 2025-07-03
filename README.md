# 🐼 Pandas 100 Medium-Level Practice Questions

---

## 🔁 Filtering & Logical Operations (1–20)

- 1. Filter rows based on multiple conditions involving columns like Salary, ExperienceYears, Location, and PerformanceRating.  
- 2. Filter employees with Salary > ₹60,000 and experience > 5 years.  
- 3. Select rows where Age < 30 and Department is 'HR'.  
- 4. Get all rows where PerformanceRating is 'Good' or 'Excellent'.  
- 5. Employees from Pune or Bangalore with Bonus > ₹15,000.  
- 6. AgeGroup is 'Senior' and LastPromotionYear < 2020.  
- 7. Employees whose Salary is between ₹50,000 and ₹80,000.  
- 8. Filter employees working in 'Data Science' with rating not 'Poor'.  
- 9. Filter all employees aged under 35 from Mumbai.  
- 10. Employees with less than 3 years experience or Salary > ₹90,000.  
- 11. Employees who are from Delhi, are over 40 years old, and have a rating of "Good".  
- 12. Employees with experience > 7 years and AgeGroup is "Senior".  
- 13. Employees with salary above average salary and bonus below 10k.  
- 14. Employees from Marketing or Sales with Rating not in ['Poor', 'Average'].  
- 15. Employees promoted in the last 2 years and earning less than 70k.  
- 16. Employees from 'HR' or 'Finance' departments with Age < 30.  
- 17. Filter based on a list of names or departments using isin().  
- 18. Find employees who are not eligible for promotion but rated 'Excellent'.  
- 19. Employees who have a non-null LastPromotionYear and salary > 90k.  
- 20. Filter those with both high salary and experience in top 10% of dataset.

---

## 📊 GroupBy & Aggregations (21–40)

- 21. Group by Department and calculate average Salary.  
- 22. Count employees in each AgeGroup.  
- 23. Total Bonus by Location.  
- 24. Max Salary in each Department.  
- 25. Min ExperienceYears by AgeGroup.  
- 26. Count employees in each Department with Rating='Excellent'.  
- 27. Average ExperienceYears grouped by Department and AgeGroup.  
- 28. Sum Bonus for employees from each city.  
- 29. Number of 'Senior' employees in each Department.  
- 30. Std deviation of Salary per PerformanceRating.  
- 31. Department-wise min and max Salary.  
- 32. Count of promotions by Department.  
- 33. Median Salary in each AgeGroup.  
- 34. Average salary by Location and Rating.  
- 35. Count employees with experience > 5 years per Department.  
- 36. Total number of employees in each Location.  
- 37. Salary variance by PerformanceRating.  
- 38. Average bonus for each AgeGroup.  
- 39. Sum of salaries of promoted vs non-promoted employees.  
- 40. Count of employees by Department and AgeGroup combination.

---

## 📈 Sorting & Ranking (41–50)

- 41. Sort the DataFrame by Salary in descending order.  
- 42. Sort by ExperienceYears, then by Age.  
- 43. Department-wise top 3 salaries using groupby + apply.  
- 44. Rank employees by Salary within each Department.  
- 45. Sort employees by LastPromotionYear.  
- 46. Sort by Bonus and PerformanceRating together.  
- 47. Rank within location for highest Salary.  
- 48. Rank by Age and Experience combined.  
- 49. Add a Salary percentile column.  
- 50. Sort based on Eligibility and then Rating.

---

## 🛠️ Column Creation using apply/lambda (51–60)

- 51. Add a Bonus column based on PerformanceRating (15%, 10%, 5%).  
- 52. Create Level based on ExperienceYears (Junior, Mid, Senior).  
- 53. Add a Tax column as 10% of Salary if Salary > ₹80,000.  
- 54. Eligibility column if employee has >3 years experience and rating = 'Good'.  
- 55. Create a RiskTag column if age > 50 and salary < ₹30,000.  
- 56. Add AgeBucket like 20s, 30s, 40s using floor division.  
- 57. Flag employees promoted within last 3 years.  
- 58. Create column: 'IncomeCategory' using Salary slabs.  
- 59. Create a Status flag using multiple column conditions.  
- 60. Round ExperienceYears to nearest integer column.

---

## ⚠️ Missing Data Handling (61–65)

- 61. Fill missing values in LastPromotionYear with 2020.  
- 62. Drop rows where Age is missing.  
- 63. Fill missing values in Salary using median.  
- 64. Use isnull() and sum() to find missing values per column.  
- 65. Replace all NaNs in ExperienceYears with 0.

---

## 🔗 Merge & Join (66–70)

- 66. Merge two DataFrames on EmployeeID (inner join).  
- 67. Merge employee info with training dataset using left join.  
- 68. Right join between HR master data and Department data.  
- 69. Combine employee and manager data on DepartmentID.  
- 70. Outer join on location data and employee salary info.

---

## 🔍 Advanced Filtering and Query Logic (71–80)

- 71. Find employees with rating='Excellent', Salary > 80k, and from Pune.  
- 72. Employees who are eligible for promotion and are not in 'HR'.  
- 73. Age between 30–40, Department='Sales', Location='Mumbai'.  
- 74. Employees promoted in the last 2 years and rating='Good'.  
- 75. Employees earning >80k and Bonus <10k.  
- 76. Use nested AND/OR to filter based on multiple logic.  
- 77. Employees with null promotion year and Age < 30.  
- 78. Use query() method for filtering complex conditions.  
- 79. Filter those having highest salary in each department.  
- 80. Filter rows where any column is null using df.isnull().any(axis=1).

---

## 🧮 Multi-Index and Multi-level Aggregation (81–85)

- 81. Group by Department + AgeGroup → count employees.  
- 82. Average Bonus grouped by Department + PerformanceRating.  
- 83. Min and Max Salary by Location + Department.  
- 84. Use named aggregations to summarize multiple metrics.  
- 85. Use groupby().agg() with dictionary to combine sum and mean.

---

## 📊 Visualization with matplotlib / seaborn (86–95)

- 86. Bar plot: Average Salary per Department.  
- 87. Pie chart: Employee distribution by AgeGroup.  
- 88. Histogram: Salary distribution.  
- 89. Box plot: Bonus by PerformanceRating.  
- 90. Countplot: No. of employees per city.  
- 91. Scatter plot: Salary vs ExperienceYears.  
- 92. Heatmap: Correlation matrix of numeric columns.  
- 93. Violin plot: Salary by Department.  
- 94. Line plot of average salary over age.  
- 95. Subplots: Salary, Experience, Bonus per group.

---

## 📁 Project-Oriented Tasks (96–100)

- 96. Perform full EDA on the HR dataset and write a summary report.  
- 97. Export top 10% earners to a separate CSV file.  
- 98. Create a pivot table showing avg Bonus by Department and Rating.  
- 99. Introduce missing data and fill using KNN or median.  
- 100. Save filtered datasets: High performers, Low performers, Not promoted.
