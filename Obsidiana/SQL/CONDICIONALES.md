
### WHERE
Nos ayuda para poner condiciones para nuestra consulta y se puede utilizar con diferentes funciones adicionales

__ *AND* __
Nos ayuda para añadir mas condiciones a nuestra consulta 
(se tienen que cumplir todas las condiciones)

__ *OR* __
Nos ayuda para añadir _mas_ condiciones a nuestra consulta 
(se tiene que cumplir al menos una de las condiciones) 

__ *NOT* __
Nos ayuda para _negar_ cualquier condición

__ *TRUE* __
Se representa como **1** y significa que la condición es _verdadera_

__ *FALSE* __
Se representa como **0** y significa que la condición es _falsa_

__ *IS* __
Se utiliza para saber si una columna es igual a un valor especifico

__ *IS NULL* __
Se utiliza para saber si una columna _si_ esta vacía

__ *IS NOT NULL* __
Se utiliza para saber si un campo *no* esta vacía

__ *IN* __
Se utiliza para saber si un campo esta dentro de un conjunto de datos

__ *BETWEEN* __
Se utiliza para saber si una columna se encuentra entre un rango

__ *LIKE* __
Se utiliza para saber si un campo contiene un dato especifico
	+ % -->  Cualquier cantidad de caracteres
	+ _  -->  Exactamente un carácter
	
		%a  Cualquier texto que termine con "a"
		a%  Cualquier texto que empiece con "a"
		%a% Cualquier texto que contenga "a"
		_a% Texto en el que el segundo carácter sea "a"
		%a__ Texto que tenga la "a" en tercer lugar desde el final

### No condicional
__ *AS* __
Se utiliza para renombrar una columna o tabla completa