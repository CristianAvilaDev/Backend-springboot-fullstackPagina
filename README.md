## **Proyecto**

Este proyecto cuenta con un backend desarrollado en Spring Boot, el cual fue contenedorizado con Docker y desplegado en un entorno de producción.  
La aplicación frontend está desarrollada en Angular, también desplegada en producción, y es la encargada de consumir los endpoints expuestos por el backend.  
El backend se conecta a una base de datos externa PostgreSQL en producción, donde gestiona operaciones CRUD (crear, actualizar y eliminar usuarios).  
Todo el sistema se encuentra completamente operativo en la nube, incluyendo el backend, el frontend y la base de datos, permitiendo que la aplicación funcione de extremo a extremo sin necesidad de configuraciones locales. Los endpoints, la persistencia de datos y la interfaz de usuario están activos y accesibles en producción.


## Frontend:

- Aplicación fronted en funcionamiento: https://inspiratendencias.netlify.app/
- - Repositorio del frontend: [Aquí](https://github.com/CristianAvilaDev/FullstackPagina-frontend-v1)
## Acceso al Backend:
- Backend en producción: [https://crudrapido-app-latest.onrender.com](https://crudrapido-app-latest.onrender.com)
  



## Características principales:

- Desarrollado utilizando Spring Boot.
- Permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) con los datos de la base de datos.
- Base de datos PostgreSQL hospedada en supabase.com.
- Diseñado para ser consumido por el frontend en Angular del proyecto FullstackPagina.
- Dockerizado: El backend está empaquetado en un contenedor Docker, lo que facilita el despliegue y ejecución en cualquier entorno compatible con Docker.
- Despliegue en Render.com, donde se ejecuta la imagen Docker en producción

## Acceso al Backend:
- Backend en producción: [https://crudrapido-app-latest.onrender.com](https://crudrapido-app-latest.onrender.com)
  
## Frontend:
- Repositorio del frontend: [Aquí](https://github.com/CristianAvilaDev/FullstackPagina-frontend-v1)
- Aplicación en funcionamiento: https://inspiratendencias.netlify.app/








## Requisitos

Antes de ejecutar el proyecto localmente, asegúrate de tener instalados los siguientes programas:

- **Java 23 o superior** 


## Instalación y despliegue local

### Clonar el repositorio

```bash
git clone https://github.com/CristianAvilaDev/FullstackPagina-backend-v1

```

### Ejecutar el backend:

 accede a:  [http://localhost:8080](http://localhost:8080/)


Notas: 

Si deseas usar una base de datos diferente, configura las propiedades de la base de datos en el archivo application.properties según corresponda.
