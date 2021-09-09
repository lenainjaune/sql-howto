# sql-howto
tout ce qui concerne SQL (SGBDR + requetes)

# Variables
```sql
SET @s = 'test' ; 
SELECT @s
-- Nota : pour utiliser avec l'opérateur LIKE, je n'ai pas réussi à faire autrement qu'inclure les %...% dans la variable ; soit SET @s = '%test%'
```
