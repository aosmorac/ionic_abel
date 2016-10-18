# ionic_abel

Instalación de de modulos con Node
----------------------------------

1. Instalar NodeJS globalmente

2. Navegar al root del proyecto

3. Instalar dependencias.


         $npm install
      
         $npm install --save-dev



Instalación de librerias con Bower.
-----------------------------------

Una vez instalados los modulos con node, se debe:

1. Instalar Bower goblamente

         $npm install -g bower"

2. Instalar librerias usadas en el proyecto.

         $bower install





Instalación de Ionic y Cordova.
-----------------------------------

1. Instalar cordova y ionic globalmente

         $npm install -g cordova ionic

2. Iniciar proyecto de Ionic

         $ionic start "myApp" tabs

3. Agregar plataforma android al proyecto

         $ionic platform add android





Tareas Gulp
------------

Instalar gulp globalmente

        $npm install -g gulp

Tareas configuradas con gulp

1. Ejecutar servidor web de desarrollo [Tarea por defecto]

        $gulp

2. Alistar los archivos rapidamente y sin comprimir para probarlos como aplicaciones mobiles

        $gulp cordovaDev



Empaquetar aplicación móvil
------------------------

Para dispositivos android ejecutar

1. Preparar android

        $ionic prepare android

2. Compilar cordodva

        $ionic compile android

3. Correr la aplicación

        $ionic run android



Manejo y descarga de archivos en dispositivo
--------------------------------------------

1. Instalar Plugins 

       $cordova plugin add org.apache.cordova.file-transfer
       $cordova plugin add cordova-plugin-file
       $cordova plugin add cordova-plugin-whitelist

