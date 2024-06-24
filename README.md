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

2. **Abre el proyecto en IntelliJ IDEA:**
- Abre IntelliJ IDEA.
- Selecciona `File` > `Open`.
- Navega hasta la ubicación donde clonaste el repositorio y selecciona el archivo `build.gradle`. Haz clic en `Open` para abrir el proyecto.

3. **Configura el perfil activo:**
- Ve a `src/main/resources/application.properties` y asegúrate de configurar adecuadamente la conexión a la base de datos PostgreSQL y otros parámetros necesarios.

4. **Ejecuta la aplicación:**
- Dentro de IntelliJ IDEA, ve al panel de Gradle (normalmente ubicado en la parte derecha).
- Expande tu proyecto > Tasks > application > bootRun y haz doble clic en `bootRun` para ejecutar la aplicación.

5. **Accede a la documentación Swagger:**
- Una vez que la aplicación esté ejecutándose, abre un navegador web.
- Ve a la siguiente URL: [http://localhost:8090/platzi-market/api/doc/swagger-ui/index.html#/](http://localhost:8090/platzi-market/api/doc/swagger-ui/index.html#/).
- Esto te llevará a la interfaz de usuario de Swagger donde puedes explorar y probar los endpoints de la API.

6. **Detener la aplicación:**
- Para detener la aplicación en IntelliJ IDEA, simplemente presiona el botón de detener en la barra de herramientas o cierra la ventana de ejecución.

¡Listo! Ahora puedes desarrollar y probar esta API utilizando IntelliJ IDEA y accediendo a la documentación con Swagger.
