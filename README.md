# Configuración inicial

1. Abre el archivo `application.properties` en la carpeta `src/main/resources`.

2. Proporciona las credenciales de tu instancia local de SQL en el archivo `application.properties`. Asegúrate de especificar la URL de la base de datos, el nombre de usuario y la contraseña adecuados.

   Ejemplo:

   ```properties
   spring.datasource.url = jdbc:sqlserver://localhost:1433;databaseName=NodoTIC;encrypt=false;trustServerCertificate=true
   spring.datasource.username = user
   spring.datasource.password = password

## Copia DB
Ejecutar script _DB CREATION.sql_ para la creación de la base de datos y las tablas correspondientes


# Conexion Java Springboot

## Descripción
Este es un proyecto de ejemplo de una aplicación Spring Boot que utiliza una base de datos SQL para gestionar datos de datos.

## Requisitos
- Java 11
- Spring Boot 2.5.0
- Base de datos SQL (Testeada en SQLServer)

## Créditos
- Contribuyentes: ADSO 6
