# Challenge Backend ONE - Conversor de Monedas G6
[![Alura Latam](https://img.shields.io/badge/Alura-Latam-blue?style=flat)](https://www.aluracursos.com/)
[![Static Badge](https://img.shields.io/badge/ONE-Oracle_Next_Education-orange?style=flat&logo=oracle&logoColor=orange)](https://www.oracle.com/co/education/oracle-next-education/) [![Static Badge](https://img.shields.io/badge/IDE-IntelliJ_IDEA-%23ff0534?style=flat&logo=IntelliJ%20IDEA&logoColor=%232196f3)](https://www.jetbrains.com/es-es/idea/) [![Static Badge](https://img.shields.io/badge/Language-Java-%23ff0000?style=flat)](#)
[![Static Badge](https://img.shields.io/badge/Java_Library-Gson_%2F_Json-blue?style=flat&logo=json)](https://mvnrepository.com/artifact/com.google.code.gson/gson)
[![Static Badge](https://img.shields.io/badge/API-Exchange_Rate_API-%23e90000?style=flat)](https://www.exchangerate-api.com/docs/java-currency-api)
[![Static Badge](https://img.shields.io/badge/license-MIT-blue)](#)

## 📋 Descripción del Proyecto
El conversor de monedas es un proyecto en Java desarrollado para la especialización Back-End G6 de Alura - Oracle Next Education. Su objetivo es permitir la conversión de valores entre distintas monedas utilizando tasas de cambio actualizadas obtenidas de una API. El usuario puede seleccionar las monedas de origen y destino, y especificar el monto a convertir. El programa se conecta a la API, obtiene la tasa de cambio actual y realiza la conversión, mostrando el resultado al usuario.

## 🛠️ Tecnologias Utilizadas
- **IntelliJ IDEA Community Edition y JDK**: Instala y configura el entorno de desarrollo Java con IntelliJ IDEA y la última versión del JDK.
- **Biblioteca Gson**: Añade la biblioteca Gson desde Maven Repository (versión 2.10.1) para manejar datos JSON.
- **Git y GitHub**: Configura Git para el control de versiones y crea un repositorio en GitHub para alojar el proyecto.
- **Postman y Trello**: Usa Postman para probar la API y Trello para gestionar las tareas del proyecto.

## 👩‍💻 Desarrollo del Proyecto
1. **Conectar y Configurar la API**: Utiliza esta API para obtener tasas de cambio actualizadas. Regístrate en el sitio web de la API, obtiene la clave API y configúrala en tu proyecto para realizar solicitudes.

2. **Implementar Funcionalidades**:
- **HttpClient y HttpRequest**: Configura HttpClient para realizar solicitudes a la API y personaliza las solicitudes con HttpRequest.
- **HttpResponse y Gson**: Gestiona las respuestas recibidas de la API usando HttpResponse. Analiza y maneja los datos JSON utilizando Gson.
- **Conversión de Monedas**: Implementa la lógica para convertir valores entre las siguientes monedas: <code>COP (Peso colombiano)</code>, <code>USD (Dólar estadounidense)</code>, <code>BRL (Real brasileño)</code> y <code>ARS (Peso argentino)</code>.

3. **Interfaz de Usuario**:Interacción mediante Consola: Crea una interfaz de consola que permita al usuario seleccionar las monedas de origen y destino, ingresar el monto a convertir y mostrar el resultado de la conversión.
   
4. **Documentación**: Documenta el proyecto en GitHub incluyendo instrucciones de uso, dependencias y una descripción del funcionamiento del conversor de monedas en un README.
   
5. **Funciones Extra**: Opcionalmene puedes añadir funcionalidades como un <code>historial de conversiones</code>, <code>soporte para más monedas</code> y <code>registros con marcas de tiempo</code> para mejorar la experiencia del usuario.

## 🚀 Cómo Ejecutar el Proyecto
Para ejecutar el proyecto, sigue estos pasos:
1. **Clona o descarga desde Github**: Clona o descarga desde Github el repositorio en tu disco local: <code>https://github.com/Latzmi-Sarmiento/ONE_Conversor-de-Monedas-G6.git</code>
2. **Importa el proyecto**: Importa el proyecto en tu IDE de Java (el proyecto se realizó en IntelliJ IDEA)y configura las dependencias y ajusta las configuraciones.
3. **Configurar la API Key**: Inserte su clave de API en la configuración del proyecto.
4. **Ejecutar el Proyecto**: Utilice su IDE favorito para compilar y ejecutar la clase <code>Principal</code>.

## ✅ Insignia de Entregado para este Challenge
![Latzmi_Badge-Conversor](https://github.com/user-attachments/assets/9b269dda-f581-4a83-a46d-613badd5433e)


## 💬 Datos de Contacto
Email: latzmisarmiento@gmail.com

Autor: Latzmi Sarmiento Palomino
