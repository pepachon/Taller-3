# Taller-3

Los tres roles creados para la base datos son:

DBA: 
	
	Creacion BD y Tablas, backups, Creacion de usuarios, Asignacion de Permisos
	Usuarios: dba_1

Analista de nomina

	Consulta de datos de empleados para pago de nomina
	Usuarios: nomina_1, nomina_2

Analista de Seleccion

	Creacion de empleados y consulta de empleados
	Usuarios: seleccion_1, seleccion_2

## Creación de roles y usuarios

A continuación, se presenta la creación de los roles y su asignación a cada uno de los usuarios:

### Creación del ROL DBA

![GitHub DBA](./Role1.PNG)

### Creación de usuario "dba_1"

![GitHub DBA](./Rol1_User1.PNG)

### Creación del rol para el análista de nomina

![GitHub nom](./Rol2.PNG)

### Creación de los usuarios "nomina_1" y "nomina_2"

![GitHub nom](./Rol2_User2.PNG)

### Creación del rol para el análista de selección

<img src="Rol3.PNG" />

### Creación de los usuarios "seleccion_1" y "seleccion_2"

<img src="Rol3_User2.PNG" />


## Verificación de privilegios

A continuación, se realiza la verificación de los privilegios de los usuarios de acuerdo con el rol asignado:

### Usuario "dba_1"

Creación exitosa de una tabla en la base de datos 

<img src="Rol_DBa.PNG" />

### Usuario "nomina_1"

Consulta exitosa de acuerdo al rol 

<img src="nom1.PNG" />

Eliminación fallida de información por falta de privilegios 

<img src="nom2.PNG" />

### Usuario "seleccion_1"

Selección exitosa de la tabla empleados 

<img src="Prueba_Select_Rol_Seleccion.PNG" />

Comando de creación de tabla fallido por falta de privilegios 

<img src="Seleecion_Privilegios.PNG" />
