# Docker

Este repositorio es para una evaluación sobre Docker! 🐳

## Resumen propio sobre Docker

[Ingrese al Resumen, haciendo click aquí](https://ten-shirt-728.notion.site/Docker-b13141cd284d4f3db86a8a52411d41f9?pvs=4)

## Proyecto Evaluativo, consigna:

Generar un docker compose, para una aplicación Wordpress con todo lo necesario.

## Explicación del codigo del docker compose

Hay 3 servicios, wordpress, mariadb y adminer.
Utilizaremos volumen, variables de entorno, puertos y compartiremos una red.

## Cómo Utilizar el repositorio

Hay que ingresar a la carpeta donde esta el archivo docker-compose, y al abrir la terminal, escribir:

```
docker-compose up -d 
```

Luego, de descargar las imagenes y hacer correr los contenedores de cada servicio. Ingresar desde el navegador a:

```
http://localhost:8060/
```

Luego de esto, instalar wordpress a preferencia (Idioma, nombre, contraseña).

Esto, te llevará a la url:

```
http://localhost:8060/wp-admin/
```

Y para ver tu página web con wordpres, ingresar:

```
http://localhost:8060/
```

Luego, ver tu base de datos desde la interfaz Adminer, para esto, ingresar a:

```
http://localhost:8061/
```

Completar los siguientes campos:

servidor=mariadb

usuario=root

contraseña=qwerty

bd=wordpress_1

### Finalmente, visualizarás tu base de datos mariadb, con las tablas de wordpress (que anteriormente instalaste) desde la interfaz adminer.

### Brian Pumarica.