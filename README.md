# consultas1_sql

#CONSULTAS SQL

![tabla usuario](img/tabla_usuario.png "tabla usuario")

1. Para visualizar toda la informacion que contiene la tabla `usuario` se puede incluir con la inclusion SELCET el caracter "*" o cada uno de los campos de la tabla
`select * from usuario`

![](img/imagen2.png "consulta 1")

2. Visualizar solamente la identificacion del usuario.

`select Identification from usuario`

![Consulta2](img/imagen4.png "consulta2")

3. Se desea obtener los registros cuya identidad sea mayores o iguales a 150, se utiliza la clausula where que especifica los condiciones que deben reunir los registros que se vam a seleccionar.

`SELECT * FROM usuario WHERE identification>='150'`

![Consulta3](img/imagen3.png "consulta3")

4. si se desea obtener los registros cuyos apellidos sean vanegas o cetinas se debe utilizar el operador in que especifica los registros que se quieren visualizar de una tabla.

`SELECT apellidos FROM usuario WHERE apellidos IN ('vanegas', 'cetina')`

![Consulta4](img/imagen5.png "consulta4")