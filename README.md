# SQL-example

# Online Sales Database System (MySQL-desktop)

This project demonstrates a transactional SQL-based backend for an online sales system using MySQL. It includes a complete schema, sample data, stored procedures with transaction management, and test cases.

## Project Structure

- `schema/create_database_and_tables.sql`: SQL script to create the database and all required tables.
- `data/insert_sample_data.sql`: Inserts sample data into the `clientes`, `productos`, `pedidos`, etc.
- `procedures/procedure_realizar_pedido.sql`: Stored procedure that handles orders with stock checks, inventory updates, and shipping registration.
- `tests/test_realizar_pedido.sql`: Test cases to validate both successful and failed order scenarios.

## Features

- Relational schema with foreign key constraints.
- Stored procedure using `START TRANSACTION`, `ROLLBACK`, `COMMIT`.
- Error handling with `SIGNAL SQLSTATE`.
- Atomic order creation including details and inventory adjustment.
- Example test cases for both valid and invalid orders.

## to Run

1. Execute `create_database_and_tables.sql` to set up the schema.
2. Load data using `insert_sample_data.sql`.
3. Create the stored procedure using the script in `procedures/`.
4. Run the tests using `test_realizar_pedido.sql`.


