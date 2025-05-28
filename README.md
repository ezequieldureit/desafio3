# Desafío #3: Configuración de IAM y S3 con AWS CLI

**Fecha de entrega:** 28/05/2025

## Objetivo

El objetivo de este ejercicio es aprender a configurar y utilizar roles de AWS IAM desde la línea de comandos (CLI) para permitir la escritura en un bucket de S3.

## Escenario

Eres un administrador de sistemas en una empresa que utiliza AWS para sus servicios en la nube. Te han asignado la tarea de configurar un rol de IAM que permita a los usuarios asumirlo desde la CLI para escribir archivos en un bucket de S3 específico.

## Requisitos

1. **Crear un bucket en S3**  
   Recuerda asignar un nombre único.
2. **Crear un rol con una política que permita escribir en el bucket creado en el paso anterior.**
3. **Generar un usuario IAM llamado `s3-support` y crear credenciales programáticas.**
4. **Actualizar la política del rol para que permita al usuario `s3-support` asumir el rol.**
5. **Conectar el CLI con las credenciales del usuario `s3-support`.**
6. **Asumir el rol y validar que puedas escribir en el bucket.**

## Documentación de referencia

- [AWS CLI Document: assume-role](https://docs.aws.amazon.com/cli/latest/reference/sts/assume-role.html)
- [Assume role credential provider](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-role.html)

## Entregables

1. **Documento con los pasos necesarios para resolver el desafío**  
   Debe contener los comandos de AWS CLI que utilizas para cada paso.
2. **Captura de la salida de comandos para asumir el rol y copiar un archivo al bucket**  
   Documenta estos comandos.
3. **Diagrama que indique cómo trabajan los objetos IAM para asumir el rol**  
   Explica brevemente en la documentación.

## Evaluación

- **Entrega en fecha.**
- **Documentación legible y comprensible para terceros.**
- **Añade material de soporte adicional.**  
  - Ejemplo: Diagrama de alto nivel.
- **Cumple con las consignas solicitadas.**
- **El entregable es funcional.**  
  - Ejemplo: el script bash al ejecutarse funciona sin errores y realiza lo solicitado.

