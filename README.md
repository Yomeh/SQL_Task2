# SQL_Task2
# Introduction
In the second and of the SQL section, I learned about retrieving data from databases using **SELECT DISTINCT** syntax, **SELECT WHERE** syntax, **OPERATORS**, and **CASE** statement. These statements perform specific functions such as retrieving specific values from columns, retrieving values from rows after meeting a specific condition, specifying multiple conditions etc.

# Skills Demonstrated
- Data Retrieval

# Objectives
1. Retrieve employee data where the city is Mumbai and Delhi.
2. Retrieve employee data where they have a and e in their first name.
3. Retrieve the data of employees who were born after 1990.
4. Sort in ascending order the list of salaries less than 1 million from the salary table.

# Methodology
![Screenshot (45)](https://github.com/Yomeh/SQL_Task2/assets/140501792/2da7772a-2c05-46c4-9de6-8cd8025ad4b8)
**1**
From the employee table, the data of employees who stayed in Mumbai and Delhi was to be retrieved. To achieve this, I made use of the following functions; **SELECT** was used in tandem with (*) to select all the columns in the table; **FROM** which specified the table we are working with which is the employee table; **WHERE** statement specifies the condition and we used the **IN** operator to create the list of the conditions to be met. The result is displayed in the image above.

**2**
![Screenshot (47)](https://github.com/Yomeh/SQL_Task2/assets/140501792/9d97c22e-bebc-494d-ba7b-ba6fb6cf6710)
From the image above, I used the **SELECT, FROM, WHERE** syntax but the condition to be met was for the fname to have an *a* and *e*. I used the **LIKE** and **AND** operators to specify that the fname should have an *a* and *e* before the result could be displayed.

**3**
![Screenshot (48)](https://github.com/Yomeh/SQL_Task2/assets/140501792/c4dff338-a462-4436-ab4f-89064e3f23e1)
To retrieve employees born after 1990 i used the **SELECT, FROM, WHERE** syntax and for the condition i specified using the **YEAR** operator on the date of birth column to be greater than *1990*. The result is displayed in the image above.

**4**
![Screenshot (49)](https://github.com/Yomeh/SQL_Task2/assets/140501792/b3ab03b3-be0f-48b6-8c02-0981f715844d)
I selected all of the columns **SELECT** from the salary table **FROM** where the condition to be met was that the base column should be more than *1 million* **WHERE**. The result is displayed in the image above.

