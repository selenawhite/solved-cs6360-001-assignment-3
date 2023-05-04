Download Link: https://assignmentchef.com/product/solved-cs6360-001-assignment-3
<br>



<strong>Database Design – Assignment 3</strong>




<strong>Part-1</strong>

<ol>

 <li>Create the tables given in following schema. Define required constraints (primary keys, foreign keys) on given tables.</li>

</ol>

Define triggered actions that will be attached to each foreign key constraint. Note: Oracle does not support “ON UPDATE”, so you only define ON DELETE. ON DELETE options supported by Oracle are “cascade” and “set null”.




<strong>* </strong>Assume we add one additional attribute to BOOK_LOANS table with name “Return_date”. When a book is borrowed, Return_date takes initial value of NULL.




<strong> </strong>

<strong> </strong>

<strong>Part-2</strong>




<ol>

 <li>Write following queries in SQL.</li>

</ol>




<ol>

 <li>For each department whose average employee salary is more than $30,000, retrieve the department name and the number of employees working for that department.</li>

</ol>




<ol>

 <li>Same as a, except output the number of male employees instead of the number of employees.</li>

</ol>




<ol>

 <li>Retrieve the names of all employees who work in the department that has the employee with the highest salary among all employees.</li>

</ol>




<ol>

 <li>Retrieve the names of employees who make at least $10,000 more than the employee who is paid the least in the company.</li>

</ol>




<ol>

 <li>Retrieve the names of employees who is making least in their departments and have more than one dependent. (solve using correlated nested queries)</li>

</ol>







<ol start="2">

 <li>Specify following views in SQL.</li>

</ol>




<ol>

 <li>A view that has the department name, manager name and manager salary for every department.</li>

</ol>




<ol>

 <li>A view that has the department name, its manager’s name, number of employees working in that department, and the number of projects controlled by that department (for each department).</li>

</ol>




<ol>

 <li>A view that has the project name, controlling department name, number of employees working on the project, and the total hours per week they work on the project (for each project).</li>

</ol>




<ol>

 <li>A view that has the project name, controlling department name, number of employees, and total hours worked per week on the project for each project with more than one employee working on it.</li>

</ol>




<ol>

 <li>A view that has the employee name, employee salary, department that the employee works in, department manager name, manager salary, and average salary for the department. (Hint: Find average salary for the department by using correlated nested query. You can have correlated nested queries also in SELECT clause.)</li>

</ol>







Part-1 is 40 points. Part-2 is 60 points. Each question in Part-2 is 6 points.





