-- --

**GROUP BY**
Se utiliza para agrupar los resultados de una consulta en base a varias columnas

_EJEMPLO_
```SQL
SELECT coin, AVG(amount) 
FROM sales 
GROUP BY coin;
```


**HAVING**
Se utiliza para filtrar los resultados de una consulta después de que se han agrupado

```SQL
SELECT coin, AVG(amount) 
FROM sales 
GROUP BY coin
HAVING AVG(amount) > 100;
```

