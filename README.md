# sql-challenge
Using records of employees of a corporation from the 1980s and 1990s in the form of six CSV files, the following is performed:


1. Data Modeling:The CSVs are inspected to sketch out an ERD of the tables using tool at (http://www.quickdatabasediagrams.com). An ERD diagram is attached as a result.

2. Data Engineering: Table schema for each of the six CSV filesis created by specifying data types, primary keys, foreign keys, and other constraints in Postgresql.Each CSV file is imported into the corresponding SQL table.

3. Data Analysis:
1. List the following details of each employee: employee number, last name, first name, gender, and salary.

2. List employees who were hired in 1986.

3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name, and start and end employment dates.

4. List the department of each employee with the following information: employee number, last name, first name, and department name.

5. List all employees whose first name is "Hercules" and last names begin with "B."

6. List all employees in the Sales department, including their employee number, last name, first name, and department name.

7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

