# Additional built-in SQL functions. Working with dates and times

## Homework Assignment Description

1. Write an SQL query that retrieves the year, month, and day from the `date` column in the `orders` table. Display them on the screen as three separate columns alongside the `id` column and the original `date` column (for a total of 5 columns).

2. Write an SQL query that adds one day to the `date` field in the `orders` table. Display the `id` field, the original `date` field, and the result of the addition on the screen.

3. Write an SQL query that, for the `orders` table and the `date` attribute, returns the number of seconds since the start of the count (i.e., its `timestamp` value). To do this, you need to find and apply the appropriate function. Display the `id` attribute, the original `date` attribute, and the result of the function on the screen.

4. Write an SQL query that counts how many rows in the `orders` table have a `date` attribute within the range from 1996-07-10 00:00:00 to 1996-10-08 00:00:00.

5. Write an SQL query that retrieves the id and date attributes from the orders table and displays them on the screen, along with a JSON object {"id": <row's id attribute>, "date": <row's date attribute>}. Use a function to create the JSON object.
