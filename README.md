1  # SQL-practice-
This screenshot shows my SQL query from Module 18, Task 2.

The goal was to find all records from the OrderDetails table where the quantity is more than 20. I used the SELECT statement to get all the fields, a WHERE condition to filter the results, and ORDER BY to sort them by ProductID.

Here is the query I used:

SELECT * 
FROM OrderDetails
WHERE Quantity > 20
ORDER BY ProductID;
