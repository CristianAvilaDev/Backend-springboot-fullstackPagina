## **Proyecto Fullstack CRUD en Producción (Spring Boot + Angular)**

Aplicación **fullstack completamente desplegada en la nube**, diseñada para demostrar un flujo real de **desarrollo, contenedorización y despliegue en producción**.

## 🧩 **Arquitectura del sistema**

- **Backend** desarrollado en **Spring Boot**,  
  ➝ **dockerizado con Docker y desplegado en producción**
- **Frontend** desarrollado en **Angular**,  
  ➝ desplegado en producción y encargado de consumir los endpoints REST del backend
- **Base de datos PostgreSQL** externa en producción

El backend gestiona operaciones **CRUD (crear, leer, actualizar y eliminar usuarios/estudiantes)** sobre la base de datos.

## ☁️ **Despliegue en la nube (End-to-End)**

Todo el sistema se encuentra **100% operativo en la nube**:

- Backend en producción
- Frontend en producción
- Base de datos en producción

La aplicación funciona **de extremo a extremo sin necesidad de configuración local**, demostrando un entorno real de producción con persistencia de datos, comunicación frontend–backend y contenedores Docker.

## 🚀 **Aplicación en producción**

- **Frontend:** [Ver aplicación]( https://frontend-springboot-proyecto.vercel.app/lista_estudiantes )
- **Backend:** https://crudrapido-app-latest.onrender.com

⚠️ **Nota:** En el primer acceso, si no aparece la lista de estudiantes, espere aproximadamente **1 minuto**.  
Render.com puede tardar en iniciar la imagen Docker debido a que se utiliza el plan gratuito.  
Después de ese tiempo, la aplicación funciona con normalidad.

- - Repositorio del frontend: [Aquí]( https://github.com/CristianAvilaDev/Frontend-springboot-proyecto.git  )

## 🛠️ **Tecnologías utilizadas**

- Java 23  
- Spring Boot  
- Angular  
- PostgreSQL  
- Docker  
- Render  
- Netlify  
- Supabase  

## ▶️ **Ejecución local**

```bash
git clone https://github.com/CristianAvilaDev/FullstackPagina-backend-v1

