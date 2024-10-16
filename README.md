# project_Documentation_SQL
SQL functions are built-in operations that allow you to perform calculations, manipulate data, and retrieve specific information from a database. They can be categorized into several types:

## Aggregate Functions and Date Functions

These functions operate on a set of values and return a single value:
•	COUNT(): Returns the number of rows that match a specified condition.
•	SUM(): Calculates the total sum of a numeric column.
•	AVG(): Computes the average value of a numeric column.
•	MAX(): Finds the maximum value in a column.
•	MIN(): Finds the minimum value in a column.

and

These functions handle date and time values:
•	DATEDIFF(): Calculates the difference between two dates.
•	DATEADD(): Adds a specified time interval to a date.
•	YEAR(): Extracts the year from a date.


### Scalar Functions and Window Functions

These functions operate on a single value and return a single value:
•	UPPER(): Converts a string to uppercase.
•	LOWER(): Converts a string to lowercase.
•	LENGTH(): Returns the length of a string.
•	ROUND(): Rounds a numeric value to a specified number of decimal places.
•	NOW(): Returns the current date and time.

and

These perform calculations across a set of rows related to the current row:
•	ROW_NUMBER(): Assigns a unique number to each row within a partition of a result set.
•	RANK(): Provides a rank to each row within a partition, with gaps for ties.


#### String Functions and  Conversion Functions

Functions specifically for manipulating string data:
•	CONCAT(): Joins two or more strings together.
•	SUBSTRING(): Extracts a part of a string based on specified positions.
•	TRIM(): Removes leading and trailing spaces from a string.

and

These functions convert data from one type to another:
•	CAST(): Converts an expression from one data type to another.
•	CONVERT(): Similar to CAST but allows for style formatting (e.g., date formats).



