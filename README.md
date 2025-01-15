# Incorrect AVG() Function Usage in SQL WHERE Clause

This example demonstrates a common error in SQL queries: attempting to use aggregate functions like AVG() directly within the WHERE clause.  Aggregate functions operate on sets of rows, while the WHERE clause filters individual rows.  This leads to a syntax error in many database systems.

The provided `bug.sql` file contains the erroneous query.  The solution, `bugSolution.sql`, shows the correct way to achieve the desired filtering using a subquery.