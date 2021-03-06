# almundo
Test front end.

Desarrollo hecho con Express como servidor, Mongosee para conexión con MongoDB, Angular para consumir servicios del Backend hecho con NodeJS de manera asincrona SPA, enrutando con angular-ui-route y maquetado Materialize css.

# Dependencias
    npm install express --save
    npm install mongoose --save
    npm install angular --save
    npm install angular-ui-router --save
    npm install materialize-css --save
    
# API Rest NodeJS
    Se arma API Rest con las siguientes funcionalidades:
    
  - La funcionalidad de listado y filtrado de hoteles esta soportada por la API y
    consumida en la aplicación cliente.
  - A la hora de diseñar la estructura de la aplicación, se tiene en cuenta factores como
    escalabilidad, reutilización y separación de responsabilidades.

# Frontend

  Se maqueta una página de resultado de hoteles, se hace diseño acorde al actual.
  Se consume la API desarrollada en el ejercicio anterior, implementando las funcionalidades
  necesarias para listar y filtar los hoteles.
  Se utiliza framework guiado por componentes (AngularJS).
  Se utiliza package manager (npm) para manejar dependencias externas.
  Se utiliza materialize y media Query para vista responsiva.
  Se optimizan la mayoría de los recursos para entornos productivos (minificar).
  
# Extras

  - Se añade capa de persistencia de datos (Angular Objetos, NodeJs).
  - Se implementa el CRUD de hoteles (solo a nivel API).
    
# Api
  POST, GET, PUT, DELET Hotels
  
# Run
  1. Instalar mogodb (#community).
  
   https://www.mongodb.com/download-center?jmp=tutorials&_ga=2.186100457.1906513914.1526957490-943148417.1526957487#community
   
  2. Luego ejecutar por consola 'mongod':
  
   > mongod
   
  3. Finalmente ejecutar por consola el proyecto desde la raiz del mismo 'node server'.
  
   > node server
   
  4. Se despleglara el proyecto por el puerto 3000.
  
   localhost:3000/
  
  
  *Note: antes de ejecutar hay que tener instalado mongo db y ejecutar el comando > mongod. Port 17072.
  
# Port 
  3000

  
