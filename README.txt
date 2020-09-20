CRUD Node.js y Postgresql

HERNEY EDUARDO QUINTERO TROCHEZ 1528556


1.Crear la tabla

CREATE TABLE pacientes (
	id SERIAL PRIMARY KEY,
	nombre VARCHAR (50) NOT NULL,
	apellido VARCHAR (50) NOT NULL, 
	numid VARCHAR (15) UNIQUE NOT NULL
)

2.ir a Postman

3.CRUD

Datos de prueba persistentes:
JSON

Crear
{
	"nombre":"juan",
	"apellido":"perez",
	"numid":"1"
}

{
	"nombre":"pepito",
	"apellido":"perez",
	"numid":"2"
}


{
	"nombre":"na",
	"apellido":"die",
	"numid":"3"
}

Actualizar
{
	"nombre":"al",
	"apellido":"guien",
	"numid":"3"
}

Eliminar
{
	"numid":"3"
}

















Datos de prueba No persistentes:
JSON

Crear
{
	"id":"1",
	"nombre":"juan",
	"apellido":"perez"
}

{
	"id":"2",
	"nombre":"pepito",
	"apellido":"perez"
}


{
	"id":"3",
	"nombre":"na",
	"apellido":"die"
}

Actualizar
{
	"id":"3",
	"nombre":"al",
	"apellido":"guien"
}

Eliminar
{
	"id":"3"
	
}
