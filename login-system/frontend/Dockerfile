# Usa una imagen de Node.js
FROM node:18

# Establece el directorio de trabajo dentro del contenedor
WORKDIR /app

# Copia los archivos de configuración de npm
COPY app/package*.json ./

# Instala dependencias
RUN npm install

# Copia el resto del código de la aplicación
COPY app ./

# Expone el puerto 3000
EXPOSE 3000

# Comando para ejecutar el frontend
CMD ["npm", "start"]

