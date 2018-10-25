## What is the UPDATE command?
The Update command is used to modify rows in a table. The update command can be used to update a single field or multiple fields at the same time. 
It can also be used to update a table with values from another table .

### Syntax:
```
UPDATE table_name
SET column1 = value1, column2 = value2, ...
WHERE condition;
```
Example:
```
UPDATE students
SET LastName = 'UPPALPATI', city = 'Hyd' where Id = 1.
```
