Instalacion BASE DE DATOS SQL SERVER:

1.Crear una base de datos en un servidor SQL Server usando el nombre Unbc2024

2.En la carpeta Scripts ejecutar los script respetando el orden numerico

Codigo fuente de framework.net:

1.Crear una carpeta nueva usando el nombre Usuarios. Posteriormente, copiar y pegar las carpetas CoreRepository, CoreService, Entities, packages, WebApp y el archivo Usuarios.sln

Publición del sitio web:
1. Abrir el archivo Usuarios.sln desde Visual Studio 2022, editar la cadena de conexion (connectionStrings) en el archivo Web.config con los datos de tu Servidor SQL Server (Data Source; initial catalog; user id;pwd)
2. Desde Visual Studio Publicar tu solucion en un Servidor IIS con frameWork o pool 4.8


