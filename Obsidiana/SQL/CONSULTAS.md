----

**SELECT**
Se utiliza para *Seleccionar* datos de una _tabla_.

	"*" Nos sirve para selecionar todas las columnas de la tabla
	SELECT * FROM;
**FROM**
Se utiliza para *Seleccionar* de que *tabla* queremos recibir los datos.

	SELECT clientes FROM;

**DISTINCT**
Se utiliza para *no repetir* datos en la consulta y solo recibir los únicos.

	SELECT DISTINCT nombre, poblacion FROM ciudad;

**ORDER BY**
Se utiliza para **ordenar** los datos de dos formas posibles.

	"DESC" ordena los datos de mayor a menor
	"ASC"  ordena los datos de menor a mayor


**LIMIT** 
Se utiliza para *limitar* la cantidad de datos que queremos recibir.

	SELECT * FROM Clientes
	LIMIT 1;

		LIMIT 1,2 --> El PRIMER parametro muestra la fila apartir de la que debe
		empezar y el SEGUNDO parametro muestra la cantidad de filas que mostrar


