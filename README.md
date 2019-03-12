# Configurar Apache

Modificar el archivo conf/tomcat-users.xml y agregar la siguiente configuración.

<user username="root" roles="manager-script,admin" password="root"/>

<role rolename="manager-gui"/>

<user username="Admin" roles="manager-gui" password="Admin"/>

