Hola mi nombre es Doroteo Gonzalez

Actualmente soy Estudiante de la ingeniería de computación Administrativa en tecmilenio y soy desarrollador de Software en EctoTec
estoy mas especializado en la gestión de base de datos.
Es por eso que quiero darles a conocer sobre la bases de datos de *Oracle* que es en la estoy enfocado

**Oracle**
Es un gestor de base de datos relacional dueño de la corporación **Oracle**, en donde permite almacenar información, normalmente son utizados por grandes y medianas empresas como YouTube, Facebook, Twitter, Google entre otros, el lenguaje de programación es *PL/SQL*.

***PL/SQL***
Es un lenguage de programación (Procedural Language/Structured Query Language) desarrollado por *Oracle*, en donde puede soportar consultas de *SQL* puro y la manipulación de datos, algunas de sus características son:

- Variables
- Estructuras Modulares
- Estructuras de control de flujo y la toma de deciones
- Manejo de excepciones (errores)

***Funciones***
La sintaxis para crear una función es de la siguiente manera
```SQL
CREATE OR REPLACE FUNCTION nombre_funcion(p_param1 tipodato)
RETURN tipo_dato IS
 -- Declaracion de variables
BEGIN
 -- Cuerpo de la función
EXCEPTION
 -- Atrapar errores
END;
```

***Procedimientos***
La sintaxis para crear un procedimiento es de la siguiente manera
```SQL
CREATE OR REPLACE PROCEDURE nombre_procedimiento(p_param1 tipodato)
 IS -- En esta ocacion no se retorna ningun valor
 -- Declaracion de variables
BEGIN
 -- Cuerpo de la función
EXCEPTION
 -- Atrapar errores
END;
```

***Creación de paquetes***
```SQL
-- Definición del (spec)
CREATE PACKAGE nombre_paquete AS
   
END nombre_paquete;
/

-- Creacion del paquete (Body)
CREATE OR REPLACE PACKAGE BODY nombre_paquete AS

END nombre_paquete;
/
```

***Creación de tablas***
```SQL
CREATE TABLE nombre_tabla
( 
  columna1 datatype [ NULL | NOT NULL ],
  columna2 datatype [ NULL | NOT NULL ],
  ...
  columna_n datatype [ NULL | NOT NULL ]
);
```
