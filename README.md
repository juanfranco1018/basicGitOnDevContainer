# Laboratorio: Entorno de Desarrollo con Dev Containers y Java

## Descripción
En este laboratorio se configuró un entorno de desarrollo aislado en VS Code mediante Dev Containers y se desarrolló una API REST básica utilizando Spring Boot y Maven.

## Entorno de Desarrollo
- **Imagen Base:** Debian Trixie (`mcr.microsoft.com/devcontainers/java:3-25-trixie`)
- **Java Version:** OpenJDK 25
- **Gestor de Construcción:** Maven 3.9.16

## Pasos Realizados
1. **Verificación de Entorno:** Se comprobó la instalación de Java y Maven dentro del contenedor.
2. **Creación del Proyecto:** Se estructuró la aplicación Spring Boot `apirest` agregando el módulo `Spring Web`.
3. **Implementación del Endpoint:** Se creó la clase `HelloController` para atender peticiones GET en la ruta `/hello`.
4. **Ejecución y Prueba:** Se inició la aplicación con `mvn spring-boot:run` y se verificó el funcionamiento enviando una solicitud HTTP mediante `curl http://localhost:8080/hello`.

## Resultado
El servicio responde con éxito el texto `Hello World`.
