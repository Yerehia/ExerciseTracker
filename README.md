# Exercise Tracker Microservice

Este microservicio proporciona una plataforma simple para que los usuarios realicen un seguimiento de sus ejercicios físicos, registrando detalles como el tipo de ejercicio, duración e intensidad. Además, ofrece estadísticas básicas sobre la actividad física del usuario.

## Funcionalidades Principales

1. **Registrar ejercicio:**
   - `POST /ejercicios`
     - Permite a los usuarios registrar un nuevo ejercicio con detalles como el tipo de ejercicio, la duración y la intensidad.

2. **Obtener lista de ejercicios:**
   - `GET /ejercicios`
     - Devuelve la lista de todos los ejercicios registrados por el usuario.

3. **Obtener estadísticas de actividad:**
   - `GET /estadisticas`
     - Proporciona estadísticas básicas sobre la actividad física del usuario, como el total de horas de ejercicio, el promedio de intensidad, etc.

4. **Eliminar ejercicio:**
   - `DELETE /ejercicios/{id}`
     - Permite a los usuarios eliminar un ejercicio específico según su identificador.

## Tecnologías Utilizadas

- **Spring Boot:** Utilizado para simplificar el desarrollo del servicio.
- **H2 Database:** Base de datos embebida para almacenar la información de los ejercicios.
- **JPA**

## Documentación de la API
La documentación detallada de la API está disponible en el archivo openapi.yaml. Puedes importar este archivo en herramientas como Swagger para explorar y probar la API.
