# Challenge Backend ONE - Conversor de Monedas G6
[![Alura Latam](https://img.shields.io/badge/Alura-Latam-blue?style=flat)](https://www.aluracursos.com/)
[![Static Badge](https://img.shields.io/badge/ONE-Oracle_Next_Education-orange?style=flat&logo=oracle&logoColor=orange)](https://www.oracle.com/co/education/oracle-next-education/) [![Static Badge](https://img.shields.io/badge/IDE-IntelliJ_IDEA-%23ff0534?style=flat&logo=IntelliJ%20IDEA&logoColor=%232196f3)](https://www.jetbrains.com/es-es/idea/) [![Static Badge](https://img.shields.io/badge/Language-Java-%23ff0000?style=flat)](#)
[![Static Badge](https://img.shields.io/badge/Java_Library-Gson_%2F_Json-blue?style=flat&logo=json)](https://mvnrepository.com/artifact/com.google.code.gson/gson)
[![Static Badge](https://img.shields.io/badge/API-Exchange_Rate_API-%23e90000?style=flat)](https://www.exchangerate-api.com/docs/java-currency-api)
[![Static Badge](https://img.shields.io/badge/test-status-%23009929?logo=github)](#)
[![Static Badge](https://img.shields.io/badge/license-MIT-blue)](#)

El conversor de monedas es un proyecto en Java desarrollado para la especialización Back-End G6 de Alura - Oracle Next Education. Su objetivo es permitir la conversión de valores entre distintas monedas utilizando tasas de cambio actualizadas obtenidas de una API. El usuario puede seleccionar las monedas de origen y destino, y especificar el monto a convertir. El programa se conecta a la API, obtiene la tasa de cambio actual y realiza la conversión, mostrando el resultado al usuario.

Pasos para el desarrollo:

Pasos para el desarrollo:
1. Entorno de Programación:
- IntelliJ IDEA:
Es un entorno de desarrollo integrado (IDE) que facilita la programación en Java. Debes instalarlo para crear y gestionar tu proyecto de manera eficiente.

- JDK (Java Development Kit):
Es necesario tener el JDK instalado para compilar y ejecutar aplicaciones Java. Asegúrate de usar una versión adecuada (17 o superior) para compatibilidad.

- Biblioteca Gson:
Gson es una biblioteca que permite la conversión de objetos Java a formato JSON y viceversa. Es crucial para manejar la respuesta de la API en este proyecto.

- Git y GitHub:
Git es un sistema de control de versiones que ayuda a gestionar el código fuente. GitHub es una plataforma que permite alojar tus repositorios. Es importante para la colaboración y seguimiento del progreso del proyecto.

- Postman:
Postman es una herramienta que facilita la prueba de APIs. Se utiliza para enviar solicitudes y verificar las respuestas de la API Exchange Rate-API antes de implementarlas en el código.

- Trello:
Trello es una aplicación de gestión de proyectos que permite organizar tareas y hacer seguimiento del progreso. Es útil para planificar el desarrollo y asignar responsabilidades.


2. Conocer la API
- Utilizar la API Exchange Rate-API:
Es fundamental estudiar la documentación de la API para comprender cómo realizar solicitudes y qué datos se pueden obtener. Esta API proporciona tasas de cambio actualizadas que se utilizarán en la conversión de monedas.

- Obtener y configurar la clave API:
Registrarse en el sitio de la API para obtener una clave de acceso es un paso necesario. Esta clave se usará en las solicitudes para autenticar el acceso a los datos.

3. Importar Gson en IntelliJ
- Añadir la biblioteca Gson desde Maven Repository (versión 2.10.1):
Para utilizar Gson en tu proyecto, debes incluirlo como una dependencia en el archivo pom.xml de Maven. Esto asegurará que la biblioteca esté disponible durante el desarrollo.

4. Construir el Cliente para Solicitudes (HttpClient)
- Configurar HttpClient para realizar solicitudes a la API:
HttpClient es la clase que permite hacer solicitudes HTTP. Debes configurarlo para establecer conexiones seguras y enviar peticiones a la API de tasas de cambio.

5. Construir la Solicitud (HttpRequest)
- Configurar HttpRequest para personalizar las solicitudes:
HttpRequest te permite definir el método HTTP, la URL y otros parámetros de la solicitud. Es esencial personalizarlo para que se ajuste a los requisitos de la API.

6. Construir la Respuesta (HttpResponse)
- Gestionar las respuestas recibidas de la API usando HttpResponse:
HttpResponse te proporciona la respuesta del servidor. Debes implementar la lógica necesaria para manejar esta respuesta, incluyendo el código de estado y el cuerpo de la respuesta.

7. Analizar la respuesta JSON
- Utilizar Gson para parsear y manejar datos JSON:
Después de recibir la respuesta en formato JSON, usar Gson para convertir estos datos en objetos Java es crucial para poder manipular la información fácilmente.

8. Monedas seleccionadas
* COP - Peso colombiano,
* USD - Dólar estadounidense
* BRL - Real brasileño
* ARS - Peso argentino:
  
9. Convertir Valores
- Implementar la lógica para convertir valores entre monedas:
Desarrollar la funcionalidad que permite al usuario ingresar una cantidad en una moneda y obtener el equivalente en otra. Esto implica utilizar las tasas de cambio obtenidas de la API.

10. Interactuar con el usuario
- Crear una interfaz de consola para la interacción:
Desarrollar una interfaz basada en consola que permita al usuario seleccionar opciones y ver resultados. Debe ser intuitiva y fácil de usar.

11. Crear un README
- Documentar el proyecto en GitHub:
El README debe incluir una descripción del proyecto, instrucciones de instalación, uso y cualquier otra información relevante. Esto es esencial para que otros desarrolladores entiendan tu trabajo.

12. Funcionalidades adicionales del Conversor de Monedas
- Historial de conversiones:
Implementar una función que registre y muestre un historial de conversiones realizadas por el usuario, mejorando la experiencia de uso.

- Soporte para la conversión de más monedas:
Añadir opciones para incluir otras monedas en futuras implementaciones, ampliando la funcionalidad del conversor.

- Registros con marca de tiempo:
Incluir la capacidad de registrar cuándo se realizaron las conversiones, lo que puede ser útil para auditorías o análisis.


Ejecución del proyecto:
- Clona el repositorio desde GitHub.
- Importa el proyecto en IntelliJ IDEA.
- Configura las dependencias y ajusta la configuración.
- Ejecuta la clase Principal para iniciar la aplicación.
  

### Insignia Exclusiva de Completado para este Challenge 
![Latzmi_Badge-Conversor](https://github.com/user-attachments/assets/9b269dda-f581-4a83-a46d-613badd5433e)


Email: latzmisarmiento@gmail.com

Autor: Latzmi Sarmiento Palomino
