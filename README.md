# BackEnd En Node

## Configuración Inicial

Para crear el archivo package.json usamos el comando npm init. En caso de que se quiera crear un archivo con información por defecto, usamos el comando npm init -y, pero modificamos el contenido del mismo.

# Estructura

El proyecto tendrá el siguiente árbol de archivos:

```
P1T1_DOS
    |___ src
        |___ config
        |___ controllers
        |___ daos
        |___ middlewares
        |___ models
        |___ repositories
        |___ routes
    |___ index.ts
```

## Primeros Paquetes

Vamos a instalar las librerías **CORS** (Cross-origin resource sharing), **Morgan** para formatear la salida en consola, **Express** para el montaje del backend, **JSONWebToken** para los token de validación, **PG-Promise** para conectarnos a PostgreSQL, con el comando ```npm i cors morgan express jsonwebtoken pg-promise.```


