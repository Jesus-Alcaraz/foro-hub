<h1 align="center"> FORO HUB </h1>


## Descripción Del Proyecto

Challenge del programa ONE de Oracle/Alura, en dónde se replica el proceso a nivel de back end; creando una API REST utilizando Spring con rutas implementadas siguiendo las mejores prácticas del modelo REST.


<p align="center"><img src="https://github.com/user-attachments/assets/745fd249-6a0c-4eba-a8df-ddcee13b42c6"></p>

## Funcionalidades

Se impementa una base de datos relacional para la persistencia de la información, se realiza las validaciones según las reglas de negocio, tiene el servicio de autenticación/autorización para restringir el acceso a la información y esta API se centra específicamente en los tópicos, y permite a los usuarios:

Crear un nuevo tópico
Mostrar todos los tópicos creados
Mostrar un tópico específico
Actualizar un tópico
Eliminar un tópico.

* Mediante autenticación es posible realizar operaciones CRUD para usuarios de distintos perfiles con sus respectivos topicos
* Permite hacer login ingresando el email y clave de usuario
* Se genera la documentación de la api mediante Swagger

## Dependencias

* Swagger
* Lombok
* Flyway
* MySql-connector
* JWT
* Spring (web,security,validation,JPA)
* Versión Java SpringBoot (Initializr) 17
* Versión Java Intellij 21

## Demostración

Se requieren crear un usuario con email y su clave en hash de tipo bcrypt en la base de datos y los perfiles.
Posteriormente hacer login y realizar nuevos registros para topicos y respuestas.

Tópicos de la aplicación

https://github.com/Gercodex/Foro-Hub-Challenge/assets/157858339/bd74e9cc-e33f-46e2-8027-17d5598d13cf



## Contacto
 * [Linkedin](https://www.linkedin.com/in/jesus-alcaraz-)
