# 🚀 Pro Task Manager API

API RESTful empresarial para la gestión de proyectos y tareas, diseñada bajo principios de **Clean Architecture**, **SOLID** y **Design Patterns**.

## 🛠️ Tecnologías y Prácticas
- **Backend:** Java 17 + Spring Boot 3.x
- **Persistencia:** Hibernate + Spring Data JPA + MySQL
- **Documentación:** Swagger UI (OpenAPI 3.0)
- **Calidad:** Validaciones con Jakarta Bean Validation
- **CI/CD:** GitHub Actions (Build & Test Automation)
- **Monitoreo de Dependencias:** Dependabot

## 🏗️ Arquitectura
El proyecto implementa una separación de capas para facilitar el testing y mantenimiento:
- **Controller Layer:** Endpoints REST con manejo de DTOs.
- **Service Layer:** Lógica de negocio desacoplada.
- **Repository Layer:** Abstracción de base de datos.
- **Global Exception Handler:** Gestión centralizada de errores HTTP.

## 🚀 Instalación y Uso
1. Clonar el repositorio.
2. Configurar `application.properties` con tus credenciales de base de datos.
3. Ejecutar `mvn spring-boot:run`.
4. Acceder a Swagger en: `http://localhost:8080/swagger-ui.html`

## ✒️ Autor
**Oscar Fuentes** - *Software Engineer* - [GitHub](https://github.com/oszkilow)