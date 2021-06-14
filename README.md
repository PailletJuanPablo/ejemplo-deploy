# Deploy de un proyecto

- Crear un repositorio en github donde subiremos el código del proyecto
- Crear una aplicación en Heroku
- Vincular el repositorio con la aplicación

- En el proyecto de Heroku, al ejecutar el método app.listen(), agregar como primer parámetro process.env.PORT || 3000.
    app.listen(process.env.PORT || 3000)

- Crear Procfile, y agregar web: comando para levantar el servidor.
    web: node app.js
    web: node index.js

