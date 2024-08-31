# Usar la última versión de Nginx
FROM nginx:latest

# Copiar los archivos del front-end al contenedor
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copiar el archivo de configuración Nginx al contenedor
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
