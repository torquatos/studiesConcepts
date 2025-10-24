1 - Database: it is a form of electronic storage in which data is held. A database is a form of electronic storage in which data is organized systematically. It stores and manipulates data electronically to make it more manageable, efficient and secure.
    
    - a database needs to allow the following actions:
        + store the data 
        + form connections or relationships between segmented areas of the data
        + filter the data to show relevant records
        + search data to return matching records
        + have functions to allow the data to be updated, changed, and deleted as required

    - a database looks like data organized systematically, this organization typically looks like a spreadsheet or a table.
        
2 - Data: it is, in basic terms, facts and figures about anything.

3 - Systematically:  that means that all data contains elements or features and attributes by which they can be identified 

4 - Relational Database: organised using tables composed by lines and columns. The Lines are the registers and the columns are the attributes.

    4.1 To interact with the relational database, we use SQL - Structure Query Language

    4.2 Most important commands:

        a. DDL - Data Definition Language

            - CREATE : used to create objects in a database 
                    ex. CREATE TABLE clients
            - ALTER: used to modify the structure of the already existing objects
                    ex. ALTER TABLE clients ADD COLUMN phone VARCHAR(25);
            - DROP: used to remove objects from the database
                    ex. DROP TABLE clients
            - TRUNCATE: used to remove all the data of a table but keeping the structure of the table. It's faster than the DELETE
                    ex. TRUNCATE TABLE

        b. DML - Data Manipulation Language

            - INSERT: used to insert new reisters in a table
            - UPDATE: used to modify data already existent in your table
            - DELETE: used to remove registers from a table
            - SELECT: used to consult data from one or more tables. It's the most used command and there are many clauses of filtring, ordering and grouping of data
