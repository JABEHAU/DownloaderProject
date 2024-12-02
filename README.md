# Downloader project
## contenido
- [Desarrolladores](#desarrolladores)
- [Resumen](#resumen)
- [Requerimientos previos](#requerimientos-previos)
- [Levantar el proyecto](#levantar-el-proyecto)
- [Resultados](#resultados)
<br>

## Desarrolladores
- **Jesus Alejandro Be Hau**
- **Roger Jesus Aguilar Uicab**
- **Miguel Angel Gomez Herguera**

---
## Resumen

Este proyecto es un descargador de música de YouTube que permite a los usuarios obtener canciones de manera rápida y sencilla. A través de una página web intuitiva, los usuarios pueden ingresar enlaces de videos y descargar el audio en formato mp3.
El sistema está diseñado para ofrecer la descarga de músicas en paralelo, brindando eficiencia para el usuario.
Para su desarrollo, se utilizaron diversas tecnologías. Django gestiona el servidor y las solicitudes de descarga, mientras que Bootstrap se empleó para crear una interfaz atractiva y fácil de usar. La lógica del programa fue implementada en Python, utilizando librerías como yt-dlp para descargar y convertir los videos en archivos de audio. Además, se desarrollaron dos versiones del programa:
La rama features/parallel_programming, que ejecuta las descargas de manera concurrente, optimizando el tiempo y los recursos.
La rama features/sequential_programming, que realiza las descargas de manera secuencial, procesando un archivo a la vez.
Estas dos versiones permiten al usuario elegir entre eficiencia máxima o un enfoque más sencillo, según sus necesidades.

---
## Requerimientos previos
Es necesario instalar python y django

---
## Levantar el proyecto

Clonar el proyecto

```bash
  git clone https://github.com/JABEHAU/DownloaderProject
```

Ir al directorio raiz del proyecto

```bash
  cd DownloaderProject
```

Lanzar el proyecto

```bash
  python manage.py runserver
```

---
## Resultados
A continuación se muestran los tiempos que tardó en ejecutarse el programa según el número de descargas, tanto de forma secuencial como de forma concurrente:
![image](https://github.com/user-attachments/assets/56ba7575-41c7-4f81-ab96-62ace5aaf4eb)
