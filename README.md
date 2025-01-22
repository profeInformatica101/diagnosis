# Proceso de Diagnóstico de una Máquina

Este proyecto proporciona un conjunto de pasos estructurados para diagnosticar el estado de una máquina en un entorno Linux. 

https://profeinformatica101.github.io/diagnosis/

A través de un conjunto de comandos esenciales, se cubren varios aspectos de la máquina, tales como el estado general del sistema, la verificación de servicios y puertos, el análisis de logs, y la comprobación de la configuración de red.

Cada sección contiene una breve explicación junto con los comandos más comunes para realizar la verificación. El proyecto está organizado mediante una estructura de acordeón (accordion) para que los usuarios puedan consultar fácilmente las distintas etapas del diagnóstico.

## Pasos incluidos

### Verificación del Estado General del Sistema
Comandos para verificar el uso de recursos del sistema, la carga de CPU, la memoria y el espacio en disco.

### Verificación de Servicios y Puertos
Comandos para comprobar el estado de los servicios y puertos activos en el sistema.

### Verificación de Logs del Sistema y Aplicaciones
Comandos para consultar los logs del sistema y de aplicaciones, como el servidor web y otros servicios.

### Verificación de la Configuración de la Red
Comandos para revisar la configuración de red, la conectividad y las configuraciones de DNS.

### Verificación de Procesos y Uso de Memoria/CPU
Comandos para ver los procesos activos y analizar el uso de CPU y memoria.

### Pruebas Específicas del Servicio
Comandos para realizar pruebas de servicios específicos como bases de datos y servidores web.

### Verificación de Virus con ClamAV
ClamAV es una herramienta para la detección de virus en sistemas Linux. A continuación se muestra cómo escanear una carpeta en busca de virus:

```bash
sudo clamscan -r /ruta/de/la/carpeta
```

- **-r**: Realiza un escaneo recursivo en la carpeta indicada.
- **/ruta/de/la/carpeta**: Sustituye por la ruta de la carpeta que deseas escanear.

Para actualizar la base de datos de ClamAV antes de realizar un escaneo, utiliza:

```bash
sudo freshclam
```

## Tecnologías utilizadas

- HTML5
- Bootstrap 5
- Bootstrap Icons

El proyecto está diseñado para ser fácil de navegar, utilizando la estructura de acordeón para un acceso rápido a los comandos y explicaciones relevantes. Ideal para administradores de sistemas y usuarios que necesiten realizar diagnósticos rápidos y eficaces.
