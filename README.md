# rpaDemo

<h2>El documento describe una demo básica para automatización de tareas con RPA.</h2>

<p>
Descripcion del escenario:</p>
<ul>
<li>Existe una pagina web con los siguientes campos: Nombre,Apellido,Telefono,Edad.http://localhost:9990/Test/.</li>
<li>Dicha información se encuentra en archivos de excel en la carpeta: C:\CreacionClientes (CreacionClientes.zip).</li>
<li>El usuario de negocio abre los archivos de excel uno por uno y copia la información en la pagina web y da click en aceptar para guardar los datos en un archivo plano, ademas va creando un archivo resultado.xlsx en la carpeta C:\ResultadoRPA que contiene el consolidado de los archivos procesados.</li>
<li>Una vez procesado el archivo es movido a la carpeta C:\CreacionClientesProcesados y eliminado de la ruta origen.</li>
</ul>


<p>Pasos para la configuración</p>
<ul>
<li>1.- Descargar el zip CreacionClientes.zip y descomprimirlo en la carpeta C:\CreacionClientes</li>
<li>2.- Crear la carpeta C:\CreacionClientesProcesados</li>
<li>3.- Crear la carpeta C:\ResultadoRPA y colocar el archivo resultado.xlsx</li>
<li>4.- Instalar el servidor Tomcat V9.0</li>
<li>5.- Colocar el contenido de la aplicacion Test(Test.zip) en la siguiente ruta: <C:\Tomcat 9.0>\webapps\Test (dependiendo de la ruta de instalacion de Tomcat) </li>
<li>5.- Descargar el archivo DemoRPAWeb.atmx que contiene la automatización</li>
<li>6.- Ejecutar el robot</li>
</ul>

<p>NOTA: Los valores de los puertos del servidor tomcat pueden cambiar según donde se ejecuten, de ser necesario corregir el script.</p>

