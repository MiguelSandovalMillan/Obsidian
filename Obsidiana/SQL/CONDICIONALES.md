---

---
---

### WHERE
Nos ayuda para poner condiciones para nuestra consulta y se puede utilizar con diferentes funciones adicionales

__ *AND* __
Nos ayuda para añadir mas condiciones a nuestra consulta 
(se tienen que cumplir todas las condiciones)

	WHERE primera condicion AND segunda condicion

__ *OR* __
Nos ayuda para añadir _mas_ condiciones a nuestra consulta 
(se tiene que cumplir al menos una de las condiciones) 

	WHERE primera condicion OR segunda condicion)

__ *NOT* __
Nos ayuda para _negar_ cualquier condición

	WHERE NOT coin = 'AGK'

__ *TRUE* __
Se representa como **1** y significa que la condición es _verdadera_

	WHERE coin IS TRUE

__ *FALSE* __
Se representa como **0** y significa que la condición es _falsa_

	WHERE coin IS FALSE

__ *IS* __
Se utiliza para saber si una columna es igual a un valor especifico

	WHERE coin IS 'AGK'

__ *IS NULL* __
Se utiliza para saber si una columna _si_ esta vacía

	WHERE coin IS NULL

__ *IS NOT NULL* __
Se utiliza para saber si un campo *no* esta vacía

	WHERE coin IS NOT NULL

__ *IN* __
Se utiliza para saber si un campo esta dentro de un conjunto de datos

	WHERE coin IN ('AGK', 'BTC', 'ETH'

__ *BETWEEN* __
Se utiliza para saber si una columna se encuentra entre un rango

	WHERE amount BETWEEN 10 AND 20

__ *LIKE* __
Se utiliza para saber si un campo contiene un dato especifico
	+ % -->  Cualquier cantidad de caracteres
	+ _  -->  Exactamente un carácter
	
		%a  Cualquier texto que termine con "a"
		a%  Cualquier texto que empiece con "a"
		%a% Cualquier texto que contenga "a"
		_a% Texto en el que el segundo carácter sea "a"
		%a__ Texto que tenga la "a" en tercer lugar desde el final


__ *AS* __
Se utiliza para renombrar una columna o tabla completa

	SELECT Ventas AS Vts