# README

## Proyecto: Aplicación Web de Pila Completa con AWS Amplify
Este proyecto es un laboratorio ubicado en [AWS Getting Started](https://aws.amazon.com/getting-started/hands-on/build-web-app-s3-lambda-api-gateway-dynamodb/). En esta tarea, se creará un modelo de datos para persistir información utilizando una API GraphQL y Amazon DynamoDB, además de usar la autorización de AWS Identity and Access Management (IAM) para otorgar de manera segura a los servicios los permisos necesarios para interactuar entre sí. También se permitirá que la función Lambda creada en la tarea anterior use la API GraphQL para escribir en la nueva tabla de DynamoDB utilizando una política IAM.


### Descripción

En este tutorial, aprender a crear una aplicación web simple de pila completa utilizando AWS Amplify. A lo largo de este tutorial, construir y alojar una aplicación de React en AWS, implementando las siguientes características:

1. **Configuración de AWS Amplify**: Configurar el proyecto para utilizar los servicios de AWS.
  
2. **Autenticación de usuarios**: Añadir un sistema de registro e inicio de sesión para que los usuarios puedan acceder a la aplicación.

3. **Gestión de datos**: Utilizar una base de datos para almacenar información del usuario, específicamente su correo electrónico.

4. **Funciones sin servidor**: Implementar una función Lambda que capturará el correo electrónico del usuario registrado y lo guardará en la base de datos.

5. **Interfaz de usuario**: Desarrollar un frontend en React que se integrará con los recursos en la nube, permitiendo a los usuarios interactuar con la aplicación.



## Pasos para Activar el Proyecto en AWS Amplify

1. **Iniciar sesión en la consola de AWS**: Acceder a la consola de AWS y buscar "AWS Amplify".

2. **Crear un nuevo proyecto**: Hacer clic en "Get Started" y conectar el repositorio de Git donde está alojado el proyecto.

3. **Configurar el flujo de trabajo**: Seguir las instrucciones para configurar el flujo de trabajo CI/CD, eligiendo las ramas a desplegar.

4. **Desplegar el proyecto**: Hacer clic en "Deploy" y esperar a que AWS Amplify construya y despliegue la aplicación.

5. **Acceder al sitio**: Una vez desplegada, se proporcionará una URL donde se puede acceder al sitio web.
