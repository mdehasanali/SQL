# Sql command in one page

### Database Showing command

```sql
SHOW DATABASE;
```

### Database Error command

```sql
SHOW ERRORS;
```

### Database Error command

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
SELECT * FROM `table_name`;
```

```sql
SELECT Collumn_Name, Collumn_Name
FROM `table_name`;
```

### Limit command

```sql
SELECT * FROM table_name LIMIT 2,5;
```

### Filtering data command

```sql
SELECT * FROM table_name LIMIT 2,5;
```
