# practica-8.1

## 1.Creación de una instancia en aws

Primero vamos a  crear un grupo de seguridad con las siguientes caracteristicas

Reglas de entrada 22: SSH (TCP),80: HTTP (TCP),443: HTTPS (TCP),ICMP,8443: (TCP)

Reglas de salida

permitir todo el tráfico de salida para cualquier dirección IP


Una vez hecho esto crearemos una instancia con las siguientes caracteristicas y le asignaremos una Ip elastica Nombre de la instancia: plesk. Imagen (AMI): Última versión disponible de Ubuntu Server. Arquitectura: x86. Tipo de instancia: t2.medium (2 vCPUs, 4 GB de RAM). Par de claves: yo pondre la mi de recuperacion2.pem. Grupo de seguridad: Crear un grupo de seguridad para plesk. Almacenamiento: 30 GB de disco EBS.