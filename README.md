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

 
## ▶️ Ejecución local

Sigue estos pasos para ejecutar el proyecto en tu máquina utilizando una base de datos PostgreSQL local.

### 📦 Requisitos previos

- Java JDK 23+
- PostgreSQL 14+
- pgAdmin
- IDE recomendado (opcional): IntelliJ IDEA

### 🚀 Pasos de instalación

#### 1️⃣ Clonar el repositorio
```bash
git clone https://github.com/CristianAvilaDev/Backend-springboot-fullstackPagina.git
```

#### 2️⃣ Crear la base de datos

- Abre pgAdmin
- Crea una nueva base de datos llamada: `bdLocal`

#### 3️⃣ Configurar application.properties

Ubica el archivo `application.properties` y elimina todo. Luego, agrega la siguiente configuración local:
```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/bdLocal
spring.datasource.username=postgres
spring.datasource.password=TU_CONTRASEÑA_DE_POSTGRES
spring.jpa.hibernate.ddl-auto=update
```

⚠️ **Asegúrate de reemplazar `TU_CONTRASEÑA_DE_POSTGRES` por tu contraseña real.**

#### 4️⃣ Ejecutar la aplicación

- Ejecuta el proyecto desde tu IDE o con Maven
- Al iniciar, Spring Boot creará automáticamente las tablas en la base de datos

### 🌐 Acceso a la aplicación

Una vez levantado el proyecto, accede desde tu navegador:

👉 http://localhost:8080

Verás un menú conectado a la base de datos local.
