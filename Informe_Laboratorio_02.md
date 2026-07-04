# Informe de Laboratorio N° 02
## Consumiendo datos de una base de datos Microsoft SQL Server

### Datos del alumno
- Nombre: Diego Fabrizio Andia Navarro
- Curso: Base de Datos II
- Fecha: 04/07/2026

### Tema
Implementación de una API REST con ASP.NET Core que consume datos desde una base de datos relacional Microsoft SQL Server contenida en Docker.

### Objetivo
Comprender el funcionamiento de una aplicación que consume una base de datos relacional contenerizada y exponer sus datos mediante una API.

### Desarrollo realizado
1. Se creó la estructura del proyecto en la carpeta ServicioCliente.
2. Se configuró un contenedor Docker con SQL Server y se inicializó la base de datos BD_CLIENTES.
3. Se generó el esquema de tablas y se cargaron datos iniciales mediante el script clientes.sql.
4. Se creó un proyecto ASP.NET Core Web API y se agregaron las dependencias de Entity Framework Core y SQL Server.
5. Se realizó el scaffolding de los modelos y del contexto de base de datos a partir de la BD existente.
6. Se generaron los controladores API para las entidades Cliente, TiposDocumento y ClientesDocumento.
7. Se configuró Swagger y la cadena de conexión para que la API pueda consumir la base de datos.
8. Se añadió un Dockerfile y se integró el servicio API en Docker Compose.

### Resultados
- La base de datos BD_CLIENTES quedó creada correctamente.
- La API quedó preparada para exponer los datos mediante endpoints REST.
- La aplicación compila correctamente con dotnet build.

### Conclusiones
El laboratorio permitió comprender cómo integrar una base de datos relacional Microsoft SQL Server con una API ASP.NET Core, utilizando contenedores Docker para facilitar la implementación y el despliegue del entorno.
