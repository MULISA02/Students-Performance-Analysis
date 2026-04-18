# Student Performance Analysis 
This project focuses on using relational database design and SQL querying to track and analyze academic performance. It moves beyond simple data storage to provide actionable insights, such as identifying top-performing students and calculating subject averages across a dataset.

Core Features
Relational Schema:Designed with a normalized structure using **Primary and Foreign Keys** to link student profiles with their academic results.
 * **Performance Metrics:** SQL scripts to calculate class averages, pass rates, and subject-specific performance.
 * **Data Insights:** Queries built to filter high-achieving students (70%+) and identify top performers using ordering and limit functions.
 * **Trend Analysis:** Utilizes aggregate functions like AVG(), COUNT(), and SUM() to provide a high-level view of student enrollment and success.
   
### ## Technical Stack
 * **Language:** SQL (Structured Query Language)
 * **Database Concepts:** Relational Mapping, Joins, Aggregations, and Data Filtering.

### ## Database Structure
The project is built around two primary tables:
 1. **Students Table:** Stores demographic data (Student ID, Name, Gender, Age).
 2. **Results Table:** Stores academic data (Subject, Score) linked via Student ID.

### ## Sample Queries Included
 * **Student Overviews:** Joining tables to create comprehensive student records.
 * **Average Calculations:** Finding the mean score for specific subjects or the entire class.
 * **High-Achiever Filters:** Isolating students who meet specific academic benchmarks.
 * **Ranking:** Identifying the highest scores across different categories.
### ## How to Use

 1. **Setup:** Run the provided schema scripts in your SQL environment (MySQL, PostgreSQL, or SQLite).
 2. **Populate:** Use the included INSERT scripts to add sample data.
 3. **Analyze:** Run the analysis scripts to generate performance reports.

