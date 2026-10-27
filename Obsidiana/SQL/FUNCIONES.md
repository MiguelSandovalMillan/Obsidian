-- -


**ROUND( )**
Redondea un Numero _(SELECT ROUND(amount, 2) FROM Sales;)_ 

	ROUND (numero a redondear , numero de decimales)


**MAX( )**
Devuelve el valor _máximo_ de una columna

	SELECT MAX(amount) FROM sales;


**MIN ( )**
Devuelve el valor _mínimo_ de una columna de una columna 

	SELECT MIN(amount) FROM sales;


**AVG ( )**
Devuelve el valor _promedio_ de una columna 

	SELECT AVG(amount) FROM sales;


**COUNT ( )**
Devuelve la _suma_ de los valores no nulos de una columna

	SELECT COUNT(*) FROM sales WHERE coin = 'AGK'

**SUM ( )**
Devuelve la _suma_ de los valores no nulos de una columna 

	SELECT SUM(amount) FROM sales;


**VALUE**
Devuelve el _valor_ de una columna especifica 

	SELECT VALUE(nombre_columna) FROM sales;

