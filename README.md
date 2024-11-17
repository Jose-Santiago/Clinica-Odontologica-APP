# Sistema de Gestión de Clínica Odontológica

Este proyecto es una aplicación desarrollada en Java utilizando Spring Boot, diseñada para gestionar eficientemente los turnos, pacientes y odontólogos en una clínica odontológica. La aplicación implementa conceptos avanzados como patrones de diseño (MVC y DAO), servicios RESTful, y un enfoque modular para facilitar su escalabilidad y mantenimiento.

## Funcionalidades principales

- **Gestión de turnos:** Registro, edición y cancelación de turnos.
- **Gestión de pacientes:** Creación, modificación y consulta de pacientes con información detallada, incluyendo domicilio.
- **Gestión de odontólogos:** Registro y mantenimiento de la información de los odontólogos.
- **Autenticación de usuarios:** Módulo de inicio de sesión para administrar roles de usuario (administradores y usuarios normales).
- **Visualización web:** Interfaz de usuario con HTML, JS y CSS para manejar los recursos del sistema.
- **Persistencia de datos:** Uso de H2 como base de datos en memoria para almacenamiento rápido y fácil configuración.

## Tecnologías utilizadas

- **Lenguaje:** Java 17
- **Framework:** Spring Boot
  - **THTML, JS y CSS:** Plantillas para las vistas.
  - **Spring Security:** Autenticación y autorización básica.
  - **Spring Web:** Implementación de endpoints RESTful.
- **Base de datos:** H2 Database
- **Herramientas:** Maven, IntelliJ IDEA, Docker (opcional para despliegue).
- **Logs:** Configuración con Log4j 2 para el registro de eventos y errores.

## Estructura del proyecto

El proyecto está organizado siguiendo el patrón de diseño MVC (Modelo-Vista-Controlador) combinado con el patrón DAO (Data Access Object) para la gestión de la persistencia de datos.

## Instalación y configuración

## Instalación y configuración

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/tu_usuario/clinica-odontologica.git
   cd clinica-odontologica
   ```
