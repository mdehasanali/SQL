# Sql command in one page

### Database Showing command

```sql
SHOW DATABASE;
```

### Database Error command

```sql
SHOW ERRORS;
```

### Database WARNINGS command

```sql
SHOW WARNINGS;
```

### Database Create command

```sql
CREATE DATABASE dataBase_name;
```

### Database Delete command

```sql
DROP DATABASE dataBase_name;
```

### Create Table command

```sql
CREATE TABLE table_name(
	column_name dataType(size)
);
```

### Rename Table command

```sql
RENAME TABLE old_table TO new_table;
```

### Delete Table command

```sql
DROP TABLE table_name;
```

### Table Details command

```sql
DESCRIBE student_info;
```

### Insert data command

```sql
INSERT INTO student_details(ID, Name, Roll)
VALUES(value-1, value-2, value-3);
```

```sql
INSERT INTO student_details
VALUES(value-1, value-2, value-3);
```

```sql
INSERT INTO student_details
VALUES(value-1, value-2, value-3),
VALUES(value-1, value-2, value-3),
VALUES(value-1, value-2, value-3),
VALUES(value-1, value-2, value-3),
```

### Insert data Showing command

```sql
SELECT *
FROM `table_name`;
```

```sql
SELECT Collumn_Name, Collumn_Name
FROM `table_name`;
```

### Limit command

```sql
SELECT *
FROM table_name
LIMIT 2,5;
```

### Filtering data command

```sql
SELECT  Collumn_Name
FROM table_name
DISTINCT;
```

### ORDER BY command by Ascending Data

```sql
SELECT * FROM
table_name
ORDER BY column_name;
```

```sql
SELECT column_name
FROM table_name
ORDER BY column_name;
```

### ORDER BY command by Descending Data

```sql
SELECT *
FROM table_name
ORDER BY column_name
DESC;
```

```sql
SELECT column_name
FROM table_name
ORDER BY column_name
DESC;
```

### WHERE Condition Chack command

```sql
SELECT *
FROM table_name
WHERE condition;
```

### AS Keyword / Custom name create command

```sql
SELECT
column_name AS "Custom_column_name",
column_name AS Custom_column_name
FROM student_info;
```

### Update Keyword command

```sql
SELECT
UPDATE table_name
SET Collumn_Name = 'VALUE'
WHERE Condition;
```

### Delete Keyword command

```sql
DELETE
FROM `table_name`
WHERE Condition
```

### Aggergate Functions Keyword command

```sql
SELECT
COUNT(Collumn_Name),
MAX(Collumn_Name),
MIN(Collumn_Name),
AVG(Collumn_Name),
SUM(Collumn_Name)
FROM table_name;
```

### SUB QUAEY Functions Keyword command

```sql
SELECT
    *
FROM
    table_name
WHERE
    Collumn_Name =>(
    SELECT
        Collumn_Name
    FROM
        table_name
);
```

```sql
SELECT
    *
FROM
    table_name
WHERE
    age >(
    SELECT
        AVG(age)
    FROM
        table_name
);
```

### Alter TABLE Add command

```sql
ALTER TABLE
    teacher ADD dept1 VARCHAR(10);
```

### Alter TABLE Rename command

```sql
ALTER TABLE
    teacher CHANGE Old_Colluam New_Colluam VARCHAR(10);
```

### Alter TABLE Remove command

```sql
ALTER TABLE
    teacher
DROP COLUMN
    Age;
```

### GROUP Keyword command

```sql
SELECT
    *
FROM
    student_info
GROUP BY
    City
ORDER BY
    City
DESC

```

### Joining Tables Keyword command

```sql
SELECT
    student_details.ID,
    NAME,
    Roll,
    Reg_number,
    Age,
    Gender,
    City
FROM
    student_details,
    student_details_2
WHERE
    student_details.ID = student_details_2.ID
```
