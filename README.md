# SQl-Query
The code you provided is a set of SQL statements that create and manage a table named customers within a schema named customer. Here's a breakdown of what each statement does:

1. Creating the Table (CREATE TABLE):

This statement defines the blueprint for your customers table. It specifies:

Columns: These are the fields that will store information about each customer.
Customer_id: A unique identifier for each customer (integer). It's marked as PRIMARY KEY, meaning no two customers can have the same ID, and it cannot be empty.
First_name: Customer's first name (text with a maximum of 20 characters). It allows empty values (null).
Last_name: Customer's last name (text with a maximum of 20 characters). It allows empty values (null).
Mobile_no: Customer's mobile number (large integer). It allows empty values (null).
Address: Customer's address (text with a maximum of 50 characters). It allows empty values (null).
2. Inserting Data (INSERT INTO):

These statements add two sample customer entries to the customers table. Each INSERT statement specifies:

Columns: The names of the columns you're inserting data into (in the same order as the values).

Values: The actual data for each column, enclosed in parentheses.

The first INSERT creates a record for customer 101 (John Doe) with a mobile number and address.

The second INSERT creates a record for customer 102 (Brad Paris) with a mobile number and address.

3. Retrieving Data (SELECT * FROM customer):

This statement retrieves all data from the customers table, including the newly inserted records.

*: Selects all columns from the table.
If you execute this code in your SQL environment, it will:

Create the customers table with the specified structure.
Insert the two sample customer records.
Display all data currently in the customers table, including the newly added entries.
