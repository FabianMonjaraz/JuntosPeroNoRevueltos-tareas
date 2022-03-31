# Tarea 4
### David Fabian Monjaraz Flores
|*Proceso*|*Descripcion*|
|:---:|---:|
|Creacion de FS|Debido a lo repetitivo de la tarea y al riesgo de hacerla de forma equivocada, esta tarea podria considerarse para ser automatizada.|
|Verificacion de espacio en FS|Si bien la tarea de liberar espacio en un FS sigue siendo mejor aplicarse manualmente, hallar los archivos que ocupan mas espacio, Verificar la utilizacion de inodes o incluso verificar si algun archivo esta eliminado pero sigue siendo utilizado por algun proceso|
|Validacion de logrotate|Aunque crear los archivos de configuracion es algo relativamente sencillo, este procesos seria mas enfocado a hacer troubleshooting de los sistemas que no esten rotando los logs. Agregar tambien de una forma mas eficientes al logrotate aquellos logs que se tengan identificados que son propensos a llenarse o incluso a eliminar aquellos logs rotados que no se eliminan despues de cierto tiempo|
|Verificacion de estado de inventarios|Para verificar si un equipo aun se encuentra activo y si cumple con los requerimientos esperados|
|Revision desde terminal de los equipos de Nagios|Si es posible generar las credenciales y los permisos suficientes, es posible crear una API para consultar los servidores de monitoreo de Nagios sin la necesidad de entrar a la interfaz web, lo que significaria tener una forma mas eficiente de obtener los equipos con problemas|
| Creación NFS: | Este proceso se puede automatizar por que es muy repetitivo e incluso ayudaria a reducir errores humanos |
| Creación de politicas de respaldo para servidores GCP: | La creacion de esta politicas puede automatizarse de manera que cada que sea creado un nuevo proyecto puedan ser creadas estas politicas|
| Asignación de espacio adicional en disco GCP: | Existe un comando que aumenta el tamaño del disco sin necesidad de hacerlo desde la consola permitiendo la automatizacion de este proceso |
| Envio de informacion por Buckets: | Este proceso es muy tardado y completamente puede ser automatizado |
