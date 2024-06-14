# Proyecto Java Spring

Este es un proyecto base utilizando Java y Spring Boot. Por favor, siga las instrucciones a continuación para configurar y ejecutar el proyecto.

## Requisitos

- JAVA 22
- Maven 3.3.0
- Git

## Configuración

Antes de ejecutar el proyecto, asegúrese de configurar el archivo `application.properties` con los datos adecuados para su entorno. Este archivo se encuentra en la ruta `src/main/resources/application.properties`.

### Ejemplo de configuración de `application.properties`

# Configuración de la base de datos
- spring.application.name=literAlura
- spring.datasource.url=jdbc:mysql://127.0.0.1/literAlura?useSSL=false&serverTimezone=UTC
- spring.datasource.username=root
- spring.datasource.password=
- spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
- spring.jpa.database-platform=org.hibernate.dialect.MySQLDialect

# Configuración de JPA/Hibernate
- spring.jpa.hibernate.ddl-auto=update
- spring.jpa.show-sql=true
- spring.jpa.format-sql=true
