# Uso de plataforma 3Dprinteros
_La plataforma de 3Dprinteros nos permite cargar archivos, editar los parámetros de impresión y supervisar la operación de las impresoras 3d de Fablab en tiempo real, esto puede realizarse con múltiples dispositivos como computadores, Tablet, e incluso smartphones. En este tutorial mostraremos los pasos a seguir para usar la plataforma de 3Dprinteros._

## La plataforma

### LOGIN

_Para iniciar sesión se debe ingresar a la página https://cloud.3dprinteros.com/ e ingresar el mail y la contraseña, respetando las mayúsculas._

<img title="login" width="1200" heigth ="600" src = "./img/login2.png">

_Ya dentro de la sesión aparecerán las siguientes pestañas._

### UPLOAD
_Esta pestaña permite subir archivos .stl para luego poder preparar el archivo de impresión.La opción Single file te permite subir un archivo para crear un nuevo proyecto, en cambio la opción Project permite añadir archivos a un proyecto existente._

<img title="UPLOAD" width="1200" heigth ="600" src = "./img/upload.png">

_Para subir un archivo se debe seleccionar la opción CHOOSE FILE la cual dependiendo del dispositivo que uses abrirá una ventana para buscar el archivo que deseas subir._

### SEARCH
_Esta pestaña permite buscar archivos .stl en páginas como Thingiverse, YouMagine, Cults, etc. para luego cargarlos e imprimirlos._ 

<img title="SEARCH" width="1200" heigth ="600" src = "./img/search.png">

### MYFILES
_En esta pestaña aparecen los archivos que has sido subidos a la plataforma. Desde esta pestaña es posible ver los archivos, generar los Gcode y enviar una impresión._

<img title="MYFILES" width="1200" heigth ="600" src = "./img/myfiles.png">

### DASHBOARD 
_Esta pestaña nos muestra información sobre las impresiones realizadas como por ejemplo el número y horas de impresión, errores, cantidad de material utilizado, etc._

<img title="DASHBOARD" width="1200" heigth ="600" src = "./img/dashboard.png">

### PRINTERS
_Esta pestaña muestra cada una de las impresoras y su estatus, además permite ver la cámara en tiempo real de cada impresora._

<img title="PRINTERS" width="1200" heigth ="600" src = "./img/printers2.png">


## Pasos a seguir para mandar una impresión 

### Cargar un archivo
_Para cargar un archivo se debe ir a la pestaña UPLOAD y seleccionar Single file si se va a subir un archivo para un nuevo proyecto o seleccionar la opción Project si el archivo que se subirá es parte de un proyecto existente._ 

<img title="UPLOAD" width="1200" heigth ="600" src = "./img/upload.png">

_Tras haber seleccionado una de las opciones se debe dar clic en la opción CHOOSE FILE la cual dependiendo del dispositivo que uses abrirá una ventana para buscar el archivo que deseas subir, en este caso trabajaremos con el archivo “DeathStarMOLDEHIELO.stl”._

<img title="UPLOAD2" width="1200" heigth ="600" src = "./img/upload2.png">

_Luego de que se haya subido el archivo se debe seleccionar la opción SAVE AND GO TO MY FILES_

<img title="UPLOAD3" width="1200" heigth ="600" src = "./img/upload4.png">

_Ya habiendo subido el archivo hay que ir a la pestaña MY FILES donde aparecerá el archivo, en este caso “DeathStarMOLDEHIELO.stl” el cual hemos subrayado en amarillo._

<img title="MYFILES2" width="1200" heigth ="600" src = "./img/myfiles2.1.png">

_El siguiente paso es preparar el diseño usando la opción LAYOUT la cual abrirá un editor de archivos stl en el cual se podrá mover, rotar y escalar el diseño a imprimir, además, es posible agregar más elementos al archivo de impresión, seleccionar el extrusor con que se imprimirá la Figura, entre otras._

<img title="LAYOUT" width="1200" heigth ="600" src = "./img/layout2.png">

_En este caso podemos ver que el archivo esta fuera de área de trabajo de la impresora por lo que debemos seleccionarlo usar las opciones ON BED la cual pondrá el diseño sobre la superficie correspondiente a la cama de impresión, luego debemos usar la función CENTER la cual pondrá el diseño en el centro de la cama de impresión, si se quisiera ubicar en otro lugar se debería usar la opción MOVE y desplazar el diseño manualmente con el mouse, flechas del teclado o en el caso de un dispositivo táctil arrastrarlo._

<img title="ON BED" width="1200" heigth ="600" src = "./img/layout-bed.png">
<img title="CENTER" width="1200" heigth ="600" src = "./img/layout-center.png">

_Luego se debe verificar las dimensiones del diseño con la opción SCALE._

<img title="SCALE" width="1200" heigth ="600" src = "./img/layout-scale.png">

_El último paso en el editor de stl es guardar el nuevo diseño, para esto está la opción SAVE la cual guardara el archivo en la carpeta del proyecto y también está la opción SAVE&SLICE la cual además de guardar el archivo abre una ventana con las opciones para realizar el slice._

<img title="LAYOUT" width="1200" heigth ="600" src = "./img/layout.png">

_El archivo guardado aparecerá en la carpeta del proyecto, en este casDeathStarMOLDEHIELO_5239562.stl_

<img title="MYPROJECT" width="1200" heigth ="600" src = "./img/myproyects3.png">


_Existe la función REPAIR que realiza automáticamente pasos anteriores, pero es recomendable confirmar luego manualmente la escala del diseño debido a posibles conflictos con las unidades de medida, para usarla se debe apretar el botón REPAIR y se abrirá la siguiente ventana en donde se debe seleccionar la opción FIX._

<img title="MYFILES3" width="1200" heigth ="600" src = "./img/myfiles3.png">

_Tras el proceso anterior ahora nuestro archivo aparecerá en la sección MY PROJECTS donde debemos seleccionar la opción SLICE en el archivo nuevo, en este caso “DeathStarMOLDEHIELO_5239562_stlmagicfix.stl”._   

<img title="MYPROJECT" width="1200" heigth ="600" src = "./img/myproyects.png">

_Luego de seleccionar la opción de SLICE se abrirá una ventana en la cual se deben ajustar los parámetros de impresión. Luego se debe seleccionar una de las 2 opciones de SLICE, es recomendable usar la opción de SLICE & toolpath preview ya que permite ver como se generara el soporte y las capas de la impresión._

<img title="SLICER" width="1200" heigth ="600" src = "./img/slicer.png">

<img title="TOOLPATH PREVIEW" width="1200" heigth ="600" src = "./img/slicer2.png">



_Luego del SLICE se generará el archivo Gcode, el cual aparecerá en la sección de MY PROJECT._

<img title="GCODE" width="1200" heigth ="600" src = "./img/gcode.png">

_Ahora se debe seleccionar la opción PRINT y se abrirá una ventana donde se deben seleccionar alguna impresora disponible_

<img title="SELECT PRINT" width="1200" heigth ="600" src = "./img/print2.png">

_Luego de esto se abrirá una ventana en la que se podrá ver el trabajo en tiempo real de la impresora, además se podrá pausar y cancelar la impresión de ser necesario._

<img title="view" width="1200" heigth ="600" src = "./img/view.jpg">
 
