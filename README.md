AsisCon 0.0.1
=======================

Aplicación móvil que sirva como asistente contable

Instalación de de modulos con Node
----------------------------------

1. Instalar Node global
2. En el root del proyecto ejecutar el comando "npm install"


Instalación de librerias con Bower.
-----------------------------------

Una vez instalados los modulos con node, se debe ejecutar:

1. Instalar bower globalmente con "npm install -g bower"
2. Instalar las librerias usadas en el prouecto con el comando "bower install"

Instalación de Cordova.
-----------------------------------

1. Instalar cordava globalmente con "npm install -g cordova"
2. Instalar plataformas y plugin para el proyecto de cordova "cordova prepare"

Caracterizticas tecnicas
------------------------

 1. AngularJS
 2. Bootstrap
 3. Cordova


Distribución de Archivos
------------------------

    /
    /app
    /app/js/                                           ->  Archivos javascript
    /app/js/controllers                                ->  Controladores de angularjs
    /app/js/directives                                 ->  Archivos js de las directivas
    /app/js/services                                   ->  Servicios de angularjs
    /app/lib                                           ->  Librerias usadas (angular, bootstrap, etc)
    /app/css/                                          ->  Hojas de estilo
    /app/img/                                          ->  Imagenes de la aplicación
    /app/views/                                        ->  Vistas de angular
    /app/views/template                                ->  Archivos HTML de la plantilla layout de la app
    /app/views/directives                              ->  Archivos HTML de las directivas 
    
