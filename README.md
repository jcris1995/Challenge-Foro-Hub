# Practicando Spring Framework: Challenge Foro Hub

![Badge Release](https://img.shields.io/badge/Release%20Date:-enero2025-blue)``
![Badge Java](https://img.shields.io/badge/Java:-17-blue)
![Badge Java](https://img.shields.io/badge/Spring%20Boot:-3.1.0-blue)
![Badge Finalizado](https://img.shields.io/badge/Status:-Finalizado-blue)

## Descrpción del proyecto

La construcción del Challenge - Foro Alura se basa en la creación de una API Rest utilizando Spring Boot para el desarrollo del back-end, MySQL como sistema de gestión de bases de datos, y Java 17 como lenguaje de programación. El desarrollo se realiza con el IDE IntelliJ, mientras que las pruebas a la API se realizan utilizando Insomnia. Este desafío corresponde al cuarto reto de la formación Oracle Next Education (ONE) de Oracle + Alura LATAM. El objetivo del reto es crear una API que implemente las mejores prácticas del modelo Rest, con validaciones personalizadas y una base de datos que garantice la persistencia de la información, enfocándose en el manejo eficiente de los tópicos y sus respuestas en un foro.

### Historia

El Foro Alura es un espacio donde los estudiantes de la plataforma pueden hacer preguntas sobre diversos cursos, fomentando el aprendizaje y la colaboración entre alumnos, profesores y moderadores. En este desafío, replicaremos el funcionamiento de este foro a nivel de Back End creando una API Rest con Spring Boot. La API se enfocará en la gestión de tópicos, permitiendo a los usuarios realizar operaciones como crear, ver, actualizar y eliminar tópicos, así como gestionar las relaciones entre los tópicos, las respuestas y los usuarios. La información se almacenará en una base de datos, asegurando la persistencia y correcta gestión de los datos.

### Funcionalidades

Funcionalidad 1: Crear un nuevo tópico.
Permite a los usuarios crear un tópico nuevo en la aplicación.

Funcionalidad 2: Mostrar todos los tópicos creados.
Muestra una lista de todos los tópicos que han sido registrados en el sistema.

Funcionalidad 3: Mostrar un tópico específico.
Permite consultar un tópico en particular mediante su identificador único.

Funcionalidad 4: Actualizar un tópico.
Facilita la actualización de la información de un tópico ya existente.

Funcionalidad 5: Eliminar un tópico.
Permite eliminar un tópico del sistema mediante su identificador.

Funcionalidad 6: API con rutas implementadas siguiendo las mejores prácticas del modelo Rest.
Se implementan rutas RESTful que permiten realizar operaciones CRUD de manera eficiente y conforme a los principios REST.

Funcionalidad 7: Validaciones realizadas según reglas del negocio.
Se implementan validaciones personalizadas para garantizar que los datos sean correctos antes de ser almacenados.

Funcionalidad 8: Implementación de una base de datos para la persistencia de la información.
Se utiliza una base de datos para almacenar los tópicos y asegurarse de que la información persista entre sesiones de usuario.

## Comenzando 

Estas indicaciones te guiarán para obtener una copia funcional del proyecto en tu máquina local, con el fin de realizar desarrollos y pruebas. Asegúrate de seguir todos los pasos para configurar correctamente el entorno de desarrollo, instalar las dependencias necesarias y ejecutar el proyecto en tu equipo. Para más información sobre cómo desplegar el proyecto en un entorno de producción, revisa la sección de Deployment.

### Pre-requisitos 

Para instalar y configurar el entorno de desarrollo, primero necesitas tener el JDK (Java Development Kit) instalado, que puedes descargar desde Oracle o OpenJDK, y verificar su instalación con java -version. También necesitas un IDE como IntelliJ IDEA, Eclipse o VS Code, que puedes descargar e instalar desde sus respectivos sitios web. Además, es recomendable contar con Maven o Gradle para gestionar dependencias y construir proyectos, y puedes verificar la instalación de Maven con mvn -version. Finalmente, necesitarás una base de datos MySQL para almacenar la información, que puedes descargar e instalar desde el sitio oficial de MySQL, y verificar la conexión con mysql -u root -p. Con estas herramientas instaladas y configuradas, estarás listo para comenzar con el desarrollo.

### Instalación 

Para configurar un entorno de desarrollo con Spring Boot, primero instala el JDK y verifica su configuración con java -version. Luego, opcionalmente instala Spring Boot CLI con Homebrew o descárgalo desde su sitio oficial. Genera un proyecto en Spring Initializr configurando dependencias como Spring Web y Spring Data JPA, y descomprímelo en tu IDE. Configura una base de datos (como MySQL), crea la base y ajusta las credenciales en application.properties. Define una entidad con JPA y un repositorio para interactuar con la base de datos. Finalmente, crea un controlador REST para probar la API y usa Postman o cURL para enviar datos, como guardar y recuperar libros, comprobando que todo funcione correctamente.

## Desarrollado con las siguientes herramientas:_

* [Trello](https://trello.com/es) - Herramienta de gestión de proyectos sugerida por Alura
* [MySQL](https://www.mysql.com/) - Sistema de gestión de bases de datos de SQL de Oracle
* [Java 17](https://www.oracle.com/java/) - Lenguaje de programación.
* [IntelliJ IDEA](https://www.jetbrains.com/idea/) -  funciona como entorno de desarrollo integrado (IDE) para el desarrollo de programas informáticos es NetBeans.
NetBeans es un IDE de código abierto que permite desarrollar aplicaciones en múltiples lenguajes de programación, como Java, PHP, HTML5, JavaScript y C/C++. Ofrece características como edición de código, depuración, refactorización y herramientas de diseño gráfico. Además, es ampliamente utilizado en entornos educativos y profesionales por su facilidad de uso, integración con bibliotecas y soporte para diversos frameworks.

* [Spring Boot](https://start.spring.io/) - Herramienta que facilita y acelera el desarrollo de aplicaciones web y microservicios al simplificar la configuración del Spring Framework mediante convenciones predeterminadas. Ofrece características como un servidor embebido (Tomcat, Jetty o Undertow), dependencias agrupadas mediante starters, soporte para monitoreo con Spring Actuator y una integración perfecta con arquitecturas de microservicios. Además, herramientas como Spring Initializr permiten generar proyectos de forma rápida y eficiente, reduciendo la complejidad y permitiendo a los desarrolladores enfocarse en la lógica de negocio.

## Autores ✒️

* **Jean Cristian Valencia García** - *Desarrollador* - [JEAN](https://www.linkedin.com/in/jean-valencia-anmdeil/)
