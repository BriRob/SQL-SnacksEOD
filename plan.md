# SQL Snacks EOD W10 D3

cd into sql directory
Run `sqlite3 dev.db` in CLI

### 1. CREATE snacks table with attributes in snacks.sql
(you can add other attributes, if you'd like)
- id (PK NOT NULL)
- name (string NOT NULL)
- type (string NOT NULL)
- description (long string)
- created at (timestamp NOT NULL)

Once created, `.read snacks.sql` in CLI
- check `.tables`

Add in snacks.sql statement to drop the snacks table if it exists


### 2. INSERT into snacks table
- First, try inserting one entry with your sqlite CLI
- You can use yesterday's snacks data as examples or make up your own!
- Make sure new entry made it into the table
    - `.headers on`
    - `.mode column` or `.mode box`
    - query for all snacks
- Next, add multiple entries into snacks table with snacks.sql
    - You can delete that original first entry in CLI or keep it before adding the insert statement in sql module
    - don't forget to .read snacks.sql and check that they all made it correctly

### 3. Query
- Snack named "Reese's Minis"
- All snacks with type of "popcorn"
- Snack with description that mentions anything with cheese


### 4. Update and DELETE snacks in CLI or in SQL file
Try this one on your own!
