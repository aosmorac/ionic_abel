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

2. Crear una carpeta llamada 'www' en el root del proyecto

3. Agregar plataforma android al proyecto

         $cordova plarform add android

4. IMPORTANTE: Crear una aplicación de ionic en una ubicación diferente a la de nuestro proyecto:

         $ionic start IonicApp blank

