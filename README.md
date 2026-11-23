# Administración de Servidores Windows – Windows Server 2022

Trabajo práctico de la materia **Sistemas Operativos 2** (Tecnicatura en Soporte de Infraestructura). Consiste en el armado de un entorno corporativo virtualizado con Windows Server 2022 y un cliente Windows 10, con servicios de directorio, red, archivos, políticas y backup.

## Entorno

| Componente | Detalle |
|---|---|
| Virtualización | Oracle VirtualBox |
| Servidor | Windows Server 2022 – IP fija |
| Cliente | Windows 10 |
| Red | Adaptador puente |
| Dominio | `empresa.local` |

## Qué se implementó

- **Active Directory:** creación del dominio `empresa.local`, unidades organizativas (OUs), usuarios y grupos.
- **DNS:** zona del dominio y resolución de nombres. El servidor es su propio DNS.
- **DHCP:** ámbito configurado para asignar direcciones a los clientes. Rango 100 - 150.
- **File Server:** carpetas compartidas con permisos por grupo y cuotas. 
- **GPO (Políticas de grupo):** fondo de pantalla, mapeo de unidades de red y restricciones del Task Manager. 
- **Backup y restauración:** copia de seguridad y restauración en vivo de archivos alojados en disco E:
- **Pruebas de funcionamiento:** ingreso del cliente al dominio, validación de GPO, permisos y restauración. 


## Aprendizajes

- Instalación y configuración de roles en Windows Server 2022.
- Administración centralizada de usuarios, equipos y permisos con Active Directory.
- Aplicación de políticas de grupo para estandarizar los equipos del dominio.
- Importancia de contar con backups probados.

## Autora

Noelia Luján – Estudiante de Soporte de Infraestructura | Soporte IT
