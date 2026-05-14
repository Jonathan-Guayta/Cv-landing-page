# Proyecto Landing Page con HTML, CSS y Nginx

## Descripción del proyecto

Este proyecto contiene una Landing Page (HTML y CSS) con imágenes (.png, .ico), servida mediante Nginx en un contenedor Docker.

---

## Estructura de carpetas

```
.
├── index.html
├── styles.css
├── L00394081.png
├── avion.ico
├── Dockerfile
├── .dockerignore
└── README.md
```

---

## Intrucciones para ejecutar el proyecto

### 1. Construir la imagen Docker
Para construir la imagen, ingresar la siguiente línea de código en la terminal del Dockerfile.

```bash
docker build -t jonag47/cv-landing-page .
```

### 2. Ejecutar el contenedor
Para ejecutar la imagen, ingresar el código en la misma terminal

```bash
docker run -d -p 8080:80 jonag47/cv-landing-page
```

### 3. Acceder al sitio en el navegador
Con la imagen ejecutada, ir a:

```
http://localhost:8080
```

---

## URL de la imagen en Docker Hub

```
https://hub.docker.com/repository/docker/jonag47/cv-landing-page/general
```

---

## Comando Docker Pull para descargar la imagen

```
docker pull jonag47/cv-landing-page
```

---

## Comando Docker Run para ejecutar el contenedor

```
docker run -d -p 8080:80 jonag47/cv-landing-page
```

---

## Notas

* Asegurarse de que los archivos (HTML, CSS) y las imágenes estén en la carpeta correcta.
* Se utiliza el puerto 8080 por defecto.

---

## Autor

Jonathan Guayta

---
