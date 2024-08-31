# Usar la última versión de Ubuntu como base
FROM ubuntu:latest

# Actualizar los paquetes del sistema
RUN apt-get update

# Mejorar los paquetes instalados
RUN apt-get upgrade -y

# Instalar Python3, pip3 y Flask
RUN apt-get install -y python3 python3-pip
RUN pip3 install flask

# Configurar el directorio de trabajo
WORKDIR /app

# Copiar el archivo api.py a la imagen Docker
COPY ./api.py /app/api.py

# Ejecutar el servidor Flask
CMD ["python3", "api.py"]
