# Student Management Database — Task 5
This project is part of my internship at Main Crafts Technology.
This task includes writing mutliple analytical SQL queries inside one single SQL file using *Window Functions* and *Advanced Analytical Techniques*.


## ✅ Task Overview

In this task, I worked with advanced SQL concepts to generate analytical insights using:

- Window Functions  
- Ranking Functions  
- Percentiles / Quartiles  
- Running (Cumulative) Averages  
- Benchmark Comparison  
- Reusable Views
All queries were executed on the Student Management Database.


## 📌 Queries Included in this project

### **1️⃣ Top 3 Performers per Course**
Uses window ranking (`RANK()` or `ROW_NUMBER()`) to fetch the top 3 students for each course.

### **2️⃣ Percentile / Quartile Banding**
Classifies students into percentiles or quartiles using `PERCENT_RANK()` or `NTILE(4)`.

### **3️⃣ Running / Cumulative Student Performance**
Calculates a student’s cumulative average across semesters using window functions.

### **4️⃣ Course Benchmark Comparison**
Compares each student's performance against semester-wise course averages.  

### **5️⃣ Reusable Views**
Two SQL views created:
- `vw_course_stats` (course averages)  
- `vw_student_ranking` (course-based student ranking)


## 📄 File Included

- [StudentManagement_Task5_reports_Riya_Kumar.sql](https://github.com/user-attachments/files/23629468/StudentManagement_Task5_reports_Riya_Kumar.sql) — SQL script with all advanced analytical queries. Contains **all Task 5 queries in one file**, separated with comments
-  [Result_Screenshots.zip](https://github.com/user-attachments/files/23629093/Result_Screenshots.zip) — Screenshots of query results
- `README.md` — project documentation 


## 🛠️ How to Use
1. Ensure your **Task 1, Task 2, Task 3 or Task 4 database setup** is already done.  
2. Open your SQL environment (MySQL, PostgreSQL, etc.)  
3. Run the SQL file:
[StudentManagement_Task5_reports_Riya_Kumar.sql](https://github.com/user-attachments/files/23629473/StudentManagement_Task5_reports_Riya_Kumar.sql)

## Technologies
- SQL
- MySQL


## Author
👩‍💻Riya Kumar - Data Analytics Enthusiast
