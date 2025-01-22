# Challenge-foro-alura

Este proyecto es una API REST para el foro de Alura, construida utilizando Spring Boot.

![Insignia](./imagenes/Badge-Spring.png)

## Requisitos

- Java 20
- Maven 3.x
- MySQL

## Tecnologías Utilizadas

- **Spring Boot 3.0.6**
- **Spring Data JPA**: Para la interacción con la base de datos.
- **Lombok**: Para reducir el código boilerplate.
- **MySQL**: Base de datos relacional.

## Instalación

1. Clona el repositorio:
    ```bash
    git clone <URL_DEL_REPOSITORIO>
    ```

2. Navega al directorio del proyecto:
    ```bash
    cd Challenge-foro-alura
    ```

3. Configura la base de datos MySQL. Crea una base de datos y actualiza las credenciales en el archivo `application.properties`:
    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/tu_base_de_datos
    spring.datasource.username=tu_usuario
    spring.datasource.password=tu_contraseña
    ```

4. Compila el proyecto utilizando Maven:
    ```bash
    ./mvnw clean install
    ```

5. Ejecuta la aplicación:
    ```bash
    ./mvnw spring-boot:run
    ```

## Uso

Una vez que la aplicación esté en funcionamiento, puedes acceder a la API REST utilizando herramientas como Postman o cURL. La URL base será `http://localhost:8080`.

## Desarrollo

Durante el desarrollo, puedes beneficiarte de las herramientas adicionales proporcionadas por `spring-boot-devtools`, como la recarga automática de la aplicación.

### Compilar y Ejecutar Pruebas

Para compilar el proyecto y ejecutar las pruebas, usa:
```bash
./mvnw test
```


---

**Conecta conmigo en alguna de mis redes sociales 🤓**

Si deseas seguir mi progreso o conectar conmigo, puedes hacerlo a través de mis redes sociales o visitar mi portafolio web:

[![LinkedIn](https://img.shields.io/badge/-LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/antonio-richaud/)
[![X](https://img.shields.io/badge/-(Twitter)-000000?style=for-the-badge&logo=X&logoColor=white)](https://twitter.com/Antonio_Richaud)
[![Youtube](https://img.shields.io/badge/-YOUTUBE-D14836?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@AntonioRichaud/)
[![TIKTOK](https://img.shields.io/badge/-TIKTOK-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@antonio_richaud)
[![Antonio-Richaud.com](https://img.shields.io/badge/-ANTONIORICHAUD.COM-8E2DE2?style=for-the-badge&logo=react&logoColor=white)](https://antonio-richaud.com/)

---
