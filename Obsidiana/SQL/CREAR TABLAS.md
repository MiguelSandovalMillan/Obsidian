[[CONDICIONALES]] - [[CONSULTAS]]

```SQL
CREATE TABLE *nombre de tabla*(
	
	Tipo de Datos y Caracteristicas

);
```

### Tipos de Datos

- **TEXT** --> Texto
- **INTEGER** --> Números Enteros
- **REAL** --> Números reales
- **VARHAR(n)** --> Limite de Caracteres
- **DECIMAL(n,m)**     n --> Dígitos en total    m--> Decimales en total
- **DATE** --> Fechas
- **CHECK** --> Booleano ( Verdadero o Falso  /  Si o No)
### Atributos de Datos

- **PRIMARY KEY** --> Llave Primaria (Atributo única e irrepetible)
- **FOREING KEY** --> Llave Foránea (Atributo tomado de otra tabla)

- **AUTOINCREMENT** --> Generar de forma sucesiva números para ID
- **NOT NULL** --> No puede ser nulo el registro

### Ejemplos

```SQL
CREATE TABLE alumno (


id INTEGER PRIMARY KEY AUTOINCREMENT,

nombre VARCHAR(100) NOT NULL,

apellido1 VARCHAR(100) NOT NULL,

apellido2 VARCHAR(100),

fecha_nacimiento DATE NOT NULL,

altura REAL NOT NULL,

promedio DECIMAL(2,2) NOT NULL,

es_repetidor TEXT CHECK(es_repetidor IN ('sí', 'no')) NOT NULL,

telefono VARCHAR(9)


);

```


```SQL

CREATE TABLE Productos (


    id_producto INTEGER PRIMARY KEY,

    nombre_producto TEXT NOT NULL,

    precio REAL NOT NULL,

    existencia INTEGER NOT NULL,

    id_categoria INTEGER,

    id_proveedor INTEGER,

    FOREIGN KEY (id_categoria) REFERENCES Categorias(id_categoria),

    FOREIGN KEY (id_proveedor) REFERENCES Proveedores(id_proveedor)


);

```