# README

## Proyecto: Aplicación Web de Pila Completa con AWS Amplify

Este proyecto es un laboratorio ubicado en [AWS Getting Started](https://aws.amazon.com/getting-started/hands-on/build-web-app-s3-lambda-api-gateway-dynamodb/).

### Descripción

En este tutorial, aprender a crear una aplicación web simple de pila completa utilizando AWS Amplify. A lo largo de este tutorial, construir y alojar una aplicación de React en AWS, implementando las siguientes características:

1. **Configuración de AWS Amplify**: Configurar el proyecto para utilizar los servicios de AWS.
  
2. **Autenticación de usuarios**: Añadir un sistema de registro e inicio de sesión para que los usuarios puedan acceder a la aplicación.

3. **Gestión de datos**: Utilizar una base de datos para almacenar información del usuario, específicamente su correo electrónico.

4. **Funciones sin servidor**: Implementar una función Lambda que capturará el correo electrónico del usuario registrado y lo guardará en la base de datos.

5. **Interfaz de usuario**: Desarrollar un frontend en React que se integrará con los recursos en la nube, permitiendo a los usuarios interactuar con la aplicación.

### Tarea adicional

En esta tarea, crear un modelo de datos para persistir datos utilizando una API GraphQL y Amazon DynamoDB. Además, utilizar la autorización de AWS Identity and Access Management (IAM) para otorgar de manera segura a los servicios los permisos necesarios para interactuar entre sí. También permitir que la función Lambda creada en la tarea anterior use la API GraphQL para escribir en la nueva tabla de DynamoDB utilizando una política IAM.

### Resumen

Este laboratorio proporciona una introducción práctica a la creación de aplicaciones web con AWS, enfocándose en la autenticación de usuarios, la gestión de datos y el uso de funciones sin servidor, garantizando la seguridad y la interconexión de servicios mediante IAM.
