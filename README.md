# sql-howto
tout ce qui concerne SQL (SGBDR + requetes)

# Variables
```sql
SET @s = 'test' ; 
SELECT @s
-- Nota : pour utiliser avec l'opérateur LIKE, faire une concaténation %...% ; soit LIKE CONCAT('%', @s, '%')
```
