# task-3-sql
Name: Shinde Abhishek Arvind 
Company: CODTECH IT SOLUTIONS 
ID:CT08OFK
Domain: SQL
Tasks Duration: January 20th,2025 to February 20th, 2025.
Mentor:Santhosh

/*We’ll create two additional tables (source_table and destination_table)*/
-- Create source table for migration since we already have source table named customers we take as the source table

![image](https://github.com/user-attachments/assets/b287ed82-e239-471d-9463-e0a6881060d0)

# Create destination table for migration

![image](https://github.com/user-attachments/assets/28419d71-6b65-44e1-97dc-75ac430464e9)

# Check data in source_table


![image](https://github.com/user-attachments/assets/b335f0da-a8be-4324-858e-eebaa9920577)


# Migrate data from source_table to destination_table

![image](https://github.com/user-attachments/assets/c48b99f4-b5a8-45c7-907c-c3ee5cf247b3)



1. The task involves migrating data from an existing source table (`customers`) to a newly created destination table (`destination_table`).
2. The `destination_table` is structured with columns such as `cust_id`, `name`, `age`, `gender`, `city`, `state`, and `memb_type`.
3. The migration query uses an `INSERT INTO` statement to copy data from `customers` into the `destination_table`.
4. Both tables (`customers` and `destination_table`) are examined using `SELECT` statements to verify data before and after migration.
5. The goal is to ensure seamless data transfer and validation between the source and destination tables.



