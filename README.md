Desafio #3
Fecha de entrega: 28/05/2025
Objetivo:
El objetivo de este ejercicio es aprender a configurar y utilizar roles de AWS IAM desde
la línea de comandos (CLI) para permitir la escritura en un bucket de S3.
Escenario:
Eres un administrador de sistemas en una empresa que utiliza AWS para sus servicios
en la nube. Te han asignado la tarea de configurar un rol de IAM que permita a los
usuarios asumirlo desde la CLI para escribir archivos en un bucket de S3 específico.
Requisitos:
1. 2. 3. 4. 5. 6. Crear un bucket en s3, recuerda asignar un nombre único.
Crear un rol con una política que permita escribir en el bucket cerrado en el paso
anterior.
Generar un usuario IAM llamado s3-support y crear una credenciales programáticas.
Actualizar la política del rol para que permita al usuario s3-support asumir el rol.
Conecta el CLI con las credenciales del usuario s3-support.
Asume el rol de válido que puedas escribir en el bucket.
Documentación de referencia:
AWS CLI Document assume-role
Assume role credential provider
Entregables:
1. 2. 3. Un documento con los pasos necesarios para resolver el desafío, el mismo debe
contener los comandos de aws cli que utilizas para cada paso.
Hacer una captura de la salida de comandos para asumir el rol y copiar un
archivo al bucket, documenta estos comandos.
Realiza un diagrama que indique cómo trabajan los objetos IAM para asumir el
role, explicarlo brevemente en la documentación.
Evaluacion:
●
●
●
●
●
Entrega en fecha.
Redactar documentación legible y que sea comprendida por terceros.
Añade material de soporte adicional.
○
Ejemplo: Diagrama de alto nivel.
Cumple con las consignas solicitadas.
El entregable es funcional.
○
Ejemplo: el script bash al ejecutarse funciona sin errores y realiza lo solicitado.
