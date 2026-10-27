-- --

**YYYY-MM-DD**
Se utiliza para guardar fechas 

	WHERE date > '2021-01-13'

**JULIANDAY**
Se utiliza para convertir una _fecha_ en un _numero decimal_ 
	
	- 2455580.5 --> significa que es medio día (12:00:00)
	- 2455580.0 --> significa que es medianoche (00:00:00)


**DATE**
Se utiliza para convertir un _numero decimal_ en una _fecha_

	SELECT DATE(2455580.5);  -->  (2011-01-13)
	
	SELECT STRFTIME('%Y-%m-%d', '2011-01-13 12:00:00');  -->  (2011-01-13)


**STRFTIME**
Se utiliza para convertir una _fecha_ en un _formato especifico_

