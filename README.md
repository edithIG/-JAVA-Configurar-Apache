# [JAVA]Configurar el administrador de Apache

Modificar el archivo conf/tomcat-users.xml y agregar la siguiente configuración.

username="root" 
roles="manager-script,admin" 
password="root"

rolename="manager-gui"
username="Admin" 
roles="manager-gui" 
password="Admin"

/EstructuraAppWeb.png
