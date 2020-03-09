FROM node:latest
    
#Directorio de trabajo de nuestra imagen
WORKDIR /usr/src/app

#Lleva todos los archivos al directorio de trabajo
COPY . /usr/src/app

#Ejecuta npm para instalar todas las dependencias del proyecto
RUN npm install

#Expone el puerto por donde se comunica mi contenedor
EXPOSE 8080

#Define que ejecuta la linea de comando, en este caso ejecuta nuestra
#aplicacion servidor.js
CMD ["node", "tareas.js"]

