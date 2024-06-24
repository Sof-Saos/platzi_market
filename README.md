# Platzi-market API

Este repositorio contiene el proyecto desarrollado durante el [Curso de Java Spring](https://platzi.com/cursos/java-spring/) en Platzi. En este curso, aprendimos a desarrollar una aplicación empresarial backend utilizando el framework más popular de Java, Spring.

## Descripción del Proyecto

El proyecto consiste en crear una API para gestionar un supermercado. Incluye la conexión a una base de datos para almacenar y recuperar información, la creación de endpoints para interactuar con los datos.

### Características

- **Conexión a Base de Datos**: Utilizamos Spring Data JPA para manejar las operaciones con la base de datos.
- **Creación de Endpoints**: Implementamos varios endpoints para las operaciones CRUD.
- **Visualización de endpoints y funcionamiento usando Swagger3**

## Requisitos

- Conocimientos en programación orientada a objetos con Java
- Experiencia en el uso de APIs
- Herramientas necesarias:
  - PostgreSQL
  - IntelliJ IDEA
  - Java SDK (versión 17)

## Ejecución del Proyecto en IntelliJ IDEA con Documentación Swagger

1. **Clonar el repositorio**:
   - Abre IntelliJ IDEA y clona el repositorio desde GitHub.

2. **Importar el proyecto**:
   - En IntelliJ IDEA, selecciona `File` > `Open` y navega hasta la carpeta del proyecto clonado. Selecciona el archivo `pom.xml` para importar el proyecto como un proyecto Maven.

3. **Configurar perfil de ejecución**:
   - Dentro de IntelliJ IDEA, abre el archivo de configuración de ejecución (usualmente en la esquina superior derecha). Asegúrate de que el perfil de ejecución esté configurado para tu aplicación Spring Boot y que el perfil activo incluya `test`.

4. **Ejecutar la aplicación**:
   - Haz clic en el botón de ejecución (usualmente un triángulo verde) para iniciar la aplicación.

5. **Acceder a la documentación Swagger**:
   - Abre un navegador web y visita la siguiente URL para acceder a la documentación Swagger:
     ```
     http://localhost:8090/platzi-market/api/doc/swagger-ui/index.html#/
     ```
   - Esto te llevará a la interfaz de usuario de Swagger donde puedes explorar y probar los endpoints de la API.

6. **¡Listo!**:
   - Ahora puedes empezar a interactuar con la API del supermercado utilizando la documentación proporcionada por Swagger.

