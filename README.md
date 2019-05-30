# INF-652-SQL-Final-Project
SQL Programming Project Exercises from Oracle Curriculum (Sections 13-16) that served as the Final for my Database Design and Programming Class


Section 13: Working with DDL Statements1.  Create tables using the attached ERD. Be sure to include the appropriate data types Rental date should default to the sysdate •Run a DESC command for each table


Section 14: Creating and Managing Constraints2.  Add the following integrity constraints:•Create primary key (PK) and foreign key (FK) constraints as needed per ERD•Create not null (NN) constraints where necessary as per ERD•Create check constraint on rating field in movie table to limit rating values to 'G', 'PG', 'R', 'PG13'•Create check constraint on category field in movie table to limit categories to 'DRAMA', 'COMEDY', 'ACTION', 'CHILD', 'SCIFI', 'DOCUMENTARY'•Run queries from the data dictionaries for the above constraints.



Section 15: Creating and Managing Views3.  Create a view called TITLE_UNAVAIL to show the movie titles and media_id of the media not returned yet.  The view should not allow any DML operations.  •Run a SELECT * for the view (after data has been added in later step)



Section 16:    Working with Sequences (Indexes and Synonyms)4.  Create the following sequences to be used for primary key values:•Use a sequence to generate PKs for CUSTOMER_ID in CUSTOMERS tableoBegin at 101 and increment by 1•Use a sequence to generate PKs for TITLE_ID in MOVIES tableoBegin at 1 and increment by 1 •Use a sequence to generate PKs for MEDIA_ID in MEDIA tableoBegin at 92 and increment by 1•Use a sequence to generate PKs for ACTOR_ID in ACTOR tablewww.oracle.com/academy
2 Copyright © 2015, Oracle and/or its affiliates. All rights reserved. Oracle and Java are registered trademarks of Oracle and/or its affiliates. Other names may be trademarks of their respective owners.oBegin at 1001 and increment by 1 •Run queries from the data dictionaries for the above sequences.5.  Add the data to the tables.  Be sure to use the sequences for the PKs.•Run a SELECT * for each table.6.  Create an index on the last_name column of the Customers table.•Run a query from the data dictionary for indexes showing this index.7.  Create a synonym called TU for the TITLE_UNAVAIL view.•Run query from the data dictionary for synonyms showing this synonym.•Print a SELECT * from the synonym.
