# rpaDemo

El documento describe una demo básica para automatización de tareas con RPA.

Descripcion del escenario:
-Existe una pagina web con los siguientes campos: Nombre,Apellido,Telefono,Edad.http://localhost:9990/Test/
-Dicha información se encuentra en archivos de excel en la carpeta: C:\CreacionClientes (CreacionClientes.zip)
-El usuario de negocio abre los archivos de excel uno por uno y copia la información en la pagina web y da click en aceptar para guardar los datos en un archivo plano, ademas va creando un archivo resultado.xlsx en la carpeta C:\ResultadoRPA que contiene el consolidado de los archivos procesados.
- Una vez procesado el archivo es movido a la carpeta C:\CreacionClientesProcesados y eliminado de la ruta origen.

Pasos para la configuración
1.- Descargar el zip CreacionClientes.zip y descomprimirlo en la carpeta C:\CreacionClientes
2.- Crear la carpeta C:\CreacionClientesProcesados
3.- Crear la carpeta C:\ResultadoRPA y colocar el archivo resultado.xlsx
4.- Instalar el servidor Tomcat V9.0
5.- Colocar el contenido de la aplicacion Test(Test.zip) en la siguiente ruta: <C:\Tomcat 9.0>\webapps\Test (dependiendo de la ruta de instalacion de Tomcat) 
5.- Descargar el archivo DemoRPAWeb.atmx que contiene la automatización
6.- Ejecutar el robot

NOTA: Los valores de los puertos del servidor tomcat pueden cambiar según donde se ejecuten, de ser necesario corregir el script.

