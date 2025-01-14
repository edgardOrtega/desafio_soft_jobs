# Servidor SoftJobs
Un servidor desarrollado con Node.js, Express y PostgreSQL para manejar la autenticación de usuarios y funcionalidades básicas de la aplicación SoftJobs.

## Descripcion
Este proyecto es un servidor backend que proporciona una API RESTful para gestionar usuarios.
- Incluye funcionalidades como registro de usuarios.
- Inicio de sesión con JWT.
- Rutas protegidas que requieren autenticación.
- Está diseñado para interactuar con una base de datos PostgreSQL.


1. Inicia el servidor:

- El servidor estará disponible en `http://localhost:3000`.

2. Endpoints disponibles:
    - **POST /usuarios**: Registra un nuevo usuario.
    - **POST /login**: Inicia sesión y genera un token JWT.
    - **GET /usuarios**: Obtiene los datos del usuario autenticado (requiere token).

3. tecnologias usadas:

    - **Node.js**: Framework de JavaScript para construir el servidor.
    - **Express.js**: Para manejar rutas y middlewares.
    - **PostgreSQL**: Base de datos relacional.
    - **bcryptjs**: Para encriptar contraseñas.
    - **jsonwebtoken**: Para la autenticación basada en tokens.
    - **dotenv**: Manejo de variables de entorno.

proyecto realizado por edgar Ortega

nota: el archivo .env no lo agregue en archivo .gitignore para que pudiera ver las variables utilizadas para este proyecto

## acotaciones

se debe levantar los dos carpetas separadas tanto para el backend y el frontend y aplicar npm i a cada uno de las carpetas para cargar el node_modules
