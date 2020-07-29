# kotlim-mis-notas

#### para ARCH Linux
Para poder conectar mi telefono tuve que instlaar un paquete en Linux

sudo pacman -Sy android-tools
sudo pacman -S android-udev

#### En el telefono
Meteser en ajustes dar 3 toques donde sale la version de android para que salga ua opcion nueva de desarrollador.
Ademas entrar a las opciones desarrollador y activar la opcion permanecer activo y la opcion Depuracion por USB
https://developer.android.com/training/basics/firstapp/running-app?hl=es-419
<br>
Si actualizas el software de tu telefono debes repetir el procedimiento. la ultima vez tuve que darle 7 veces a la compilacion del telefono y salio 
la opcion de desarrollador

##configuraciones del IDE
mostramos el toolbar
click en view >> appearance >> Toolbar


#### Instale un plugin y luego me dio Error y no pude abrir mas el IDE de Android studio
yo uso GNU Linux.. busque la carpeta de onfiguracion y la borre se encuentre en /home/$USER/.AndroidStudio4.0

#### Comandos para ADB
para eliminar la conexion con la adb.
adb kill-server

para iniciar la conexion con la adb.
adb start-server
