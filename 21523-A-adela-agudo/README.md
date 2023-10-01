# Argentina Programa 4.0
# Comision 21523-A

## Blog creado con el fin de crear y compartir publicaciones de temas variados en una página web personal. 
## Las publicaciones incluyen un título descriptivo, contenido informativo, una fecha de creación y la opción de adjuntar el link de una imagen de internet para relacionarla con el contenido. 

# Proyecto Final Lenguajes de programación 1 
# EPICA SAPEM 
# Full Stack 

 # Implementando:
 Node.js con Express y Sequelize para interactuar con MySQL y EJS.
 Uso de HTML- CSS- BOOSTRAP

## Servidor Express

![Node Express](https://somospnt.com/images/blog/zojuy79lo3fn3qdt7g6p.png)


# PASOS

<<< Configurar el entorno >>>

    -Instalar Node.js y NPM si aún no lo han hecho.
    -Crear un nuevo directorio y configurar un archivo package.json utilizando el comando "npm init".


<<< Instalar las dependencias >>>

     . Express (Framework web de Node.js.)

     . Cors (Middleware para habilitar el acceso a recursos en diferentes dominios (CORS))

     . Dotenv (opcional. Para cargar variables de entorno desde un archivo `.env`.)

     . Helmet

     . Morgan (Middleware para registrar solicitudes HTTP.)

     . EJS

     . Sequelize (ORM (Object-Relational Mapping) para interactuar con la base de datos.) 

     . mysql2 ( Controlador MySQL para Sequelize.)

     . Configurar los Middlewares necesarios.

     . Configurar la conexión a la base de datos utilizando Sequelize.


<<< Configurar variables de entorno >>>

-Crear y configurar un archivo “.env” para implementar variables de entorno.


<<< Crear rutas y controladores >>>

-Definir las rutas para las diferentes operaciones CRUD (Crear, Leer, Actualizar y Eliminar) en el archivo principal de rutas.
-Crear controladores para manejar la lógica de cada ruta, que incluya la manipulación de los posts en la base de datos utilizando Sequelize.


<<< Crear las vistas EJS >>>

- Bootstrap para estructurar el diseño general de la página.

- Agregar CSS manual.

- Crear una vista para el formulario de creación de posts, utilizando elementos de formulario y estilos de Bootstrap.

- Crear una vista para mostrar la lista de posts, utilizando componentes de Bootstrap para dar formato a los posts.

- Mostrar en la vista los siguientes datos de cada post: 

   .Título del post

   .Contenido del post

   .Imagen relacionada con el link que se coloca en el formulario
   
   .Fecha de creación del post.


<<< Implementar el formulario y el CRUD >>>

- Crear el formulario HTML en la vista EJS para agregar nuevos posts.

- Utilizar JavaScript para enviar los datos al servidor y crear nuevos posts en la base de datos.

- Implementar operaciones CRUD adicionales en la vista y los controladores para editar y eliminar posts utilizando JavaScript y comunicándose con el servidor.

 
  ## si clonas el repositorio:

         <<<   GIT    >>>

        .Elimina el archivo ".git" de la carpeta donde clonaste el repositorio.
        
        .En la terminal de tu editor de codigo utiliza el comando "git init" (se crea automaticamente la carpeta ".git")

        .Se sigue con los comandos correspondientes a GIT


        <<< NPM >>>
        
        .En la terminal ingresar el comando "npm i" donde automaticamente se instalaran las dependencias correspondientes.


        <<< DATA BASE >>>

        .Conectar XAMPP
        .Abrir PHPMyadmin en el navegador
        .Crear el archivo correspondiente con sus celdas (en este caso son 5: Id, titulo, descripcion, fecha, url_imagen)
        .Desde tu editor de codigo ir a la carpeta "database.js" y cambiar el nombre del archivo por el que creaste

        <<< FINAL >>>
        
        -En la terminal de tu editor de codigo poner "npm run dev" lo cual si todo esta OK te devolvera el host del servidor.
        -Copiar el servidor y abrir en navegador.