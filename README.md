# DragonWebeloper
DragonWebeloper es un framework para creación de sitios web estáticos desarrollado mediante el uso de tecnologías como: Jade, Less, Prepros/CodeKit, Semantic.gs, Lesshat, Responsiveslides...

## Hola Dragón

1.  Clonar el repositorio o descargarlo del lado derecho en el botón "Download ZIP".
2.  Descomprimir y renombrar carpeta por nombre del sitio. Colocar en folder para desarrollar.
3.  Arrastrar carpeta a precompilador de less/jade (Prepros / Codekit).
4.  Configurar la compilación de archivos **.jade** para que el *output* redireccione hacia ROOT en la carpeta principal. Es decir, al compilar los **.jade** dentro de **_/jade/** debe compilar los **.html** en la carpeta general del sitio.


### Estructura

.DragonWebeloper
|-- _


    |-- css

        |-- _

            |-- customs.less

            |-- grid.less

            |-- lesshat.less

            |-- mediaqueries.less

            |-- reset.less

            |-- responsiveslides.less

        |-- **style.less**

        |-- **style.css**                 # Compilado desde style.less

    |-- img

    |-- jade

        |-- _config.jade

        |-- _mixins.jade

        |-- **index.jade**

    |-- js

        |-- _

            |-- jquery.js

            |-- responsiveslides.js

        |-- _script.js

    |-- php

        |-- mail.php

|-- **index.html                          # Compilado desde index.jade


## Configuración

##
