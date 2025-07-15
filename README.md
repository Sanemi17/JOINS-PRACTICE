# JOINS-PRACTICE

COMPANY NAME: CODTECH IT SOLUTIONS


NAME: SANEMI VALECHA


INTERN ID : CT04DZ135


DOMAIN NAME: SQL


DURATION: 4 WEEKS


MENTOR: NEELA SANTOSH


In relational databases, data is often stored in multiple tables that are logically related to each other. To retrieve meaningful information, it is crucial to combine this data based on relationships between tables. This process is accomplished using SQL JOIN operations, which are among the most powerful features in Structured Query Language (SQL). The purpose of Task 1 was to perform and demonstrate four different types of joins — INNER JOIN, LEFT JOIN, RIGHT JOIN, and FULL OUTER JOIN — to combine data meaningfully and retrieve complete results based on table relationships.

During this task, I worked with two sample tables: Employees and Departments. The Employees table contained basic information about employees including their name and department ID, while the Departments table contained department names associated with each department ID. The key relationship between these tables was established through the DepartmentID column. This column existed in both tables and acted as a foreign key in the Employees table, pointing to the Departments table.

💡 Understanding and Demonstrating Each Join:
INNER JOIN:

The INNER JOIN returns only those records where there is a match between the two tables. If an employee does not belong to a department or a department is not assigned to any employee, that data is not shown.

Example: I used an INNER JOIN to retrieve employee names along with their respective department names, only where the department ID matched in both tables.

LEFT JOIN (or LEFT OUTER JOIN):

The LEFT JOIN returns all records from the left table (Employees), and the matched records from the right table (Departments). If there is no match, the result is NULL on the side of the right table.

This was useful to display all employees, including those who have not been assigned a department.

RIGHT JOIN (or RIGHT OUTER JOIN):

The RIGHT JOIN is the reverse of LEFT JOIN. It returns all records from the right table (Departments) and the matched records from the left table (Employees). Where no match exists, NULL values are returned for columns from the left table.

This helped identify departments that do not yet have any employees assigned.

FULL OUTER JOIN:

The FULL OUTER JOIN combines the results of both LEFT and RIGHT joins. It returns all records when there is a match in either the left or right table. Where there is no match, the result will contain NULLs.

This join was most useful when we wanted to ensure no data was left out — showing all employees and all departments, regardless of whether a match existed.

🔎 Practical Applications:
The JOIN operations are fundamental in real-world applications such as HR systems, e-commerce platforms, school management systems, and any other domain that relies on relational databases. For instance:

INNER JOIN is commonly used in reports where only relevant matched data is needed.

LEFT JOIN helps display optional or missing information (e.g., employees without departments).

RIGHT JOIN helps identify unused categories (e.g., departments without employees).

FULL OUTER JOIN is best for audits or when you need a comprehensive view combining both matched and unmatched records.

🧠 What I Learned:
Through this task, I developed a deeper understanding of how data in normalized relational databases can be combined for meaningful insights. I understood the importance of join conditions, the role of primary and foreign keys, and how different joins serve different analytical purposes. It also enhanced my skills in writing efficient SQL queries, understanding NULL values, and working with real-world-like relational datasets.

In conclusion, Task 1 was not only about practicing joins but also about understanding the core philosophy of relational data retrieval. Joins are essential for connecting the dots in a database and making raw data useful for analysis and reportiING. This task was a great foundation for more complex SQL operations that follow in later tasks.


OUTPUTS


"https://github.com/user-attachments/assets/0875e9eb-5831-4ebd-829c-9794654d9067"


"https://github.com/user-attachments/assets/5e5a6635-52e9-42ed-b508-59ce9db02be5"


"https://github.com/user-attachments/assets/c5ecdd73-e3c7-4b54-ac70-951a91247073"


"https://github.com/user-attachments/assets/2a391688-ebb0-44a6-b58a-6cc118495f90"
