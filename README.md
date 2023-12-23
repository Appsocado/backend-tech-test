## Descripción del Coding Challenge

El desafío de programación consiste en el desarrollo de dos microservicios: `user` y `task`.

### Microservicio `user`

El microservicio `user` cuenta con dos endpoints principales:

1. **create-user:** Este endpoint crea un usuario en la base de datos.
2. **authenticate:** Valida la existencia del usuario en la base de datos y devuelve información del usuario junto con un token de autenticación.

Se sugiere utilizar una base de datos en memoria, como SQLite, para almacenar la información de los usuarios.

#### Funcionalidades:

- `create-user`: Crea un nuevo usuario en la base de datos.
- `authenticate`: Valida la existencia del usuario en la base de datos y devuelve información del usuario junto con un token de autenticación.

#### Nice to Have (Opcionales):

1. **Comunicación entre microservicios:** Implementar comunicación basada en eventos utilizando tecnologías como Kafka para facilitar la interacción entre los microservicios.
2. **Configuración de event-caching:** Utilizar Redis para configurar un sistema de almacenamiento en caché de eventos.
3. **Dockerización:** Emplear Docker para contenerizar el microservicio, facilitando así su despliegue y administración.

### Microservicio `task`

El microservicio `task` ofrece operaciones CRUD (Create, Read, Update, Delete) para tareas. Cada uno de sus endpoints requiere autenticación antes de ejecutarse.

Se sugiere utilizar una base de datos en memoria, como SQLite, para almacenar la información relacionada con las tareas.

#### Funcionalidades:

- Operaciones CRUD para tareas. Se necesita autenticación para ejecutar cada uno de estos endpoints.

#### Nice to Have (Opcionales):

1. **Comunicación entre microservicios:** Implementar comunicación basada en eventos utilizando tecnologías como Kafka para facilitar la interacción entre los microservicios.
2. **Configuración de event-caching:** Utilizar Redis para configurar un sistema de almacenamiento en caché de eventos.
3. **Dockerización:** Emplear Docker para contenerizar el microservicio, facilitando así su despliegue y administración.
