# Como nosotros necesitamos una imagen con un servidor web
# vamos a traer un servicio de servidor web, en este caso nginx
FROM nginx:latest
# La palabra reservada FROM hara un pull de nginx

# Ahora copiaremos los archivos html a el servidor web
# nginx es una imagen basada en linux por lo que se usa la estructura de archivos de linux
# Path: /usr/share/nginx/html --> Todos los archivos que html que coloquemos aqui se van a volver un sitio web
COPY /linktree /usr/share/nginx/html
