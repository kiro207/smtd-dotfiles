*Aquí generar el menú sin iconos*
--Primero instalar las dependencias--
$ sudo apt install build-esscential
-------------------------------------
Instalar con cpan:
$ cpan Module::Build
$ cpan Data::Dumper
$ cpan Linux::DesktopFiles
-------------------------------------
Copiar la configuración a la carpeta correspondiente y luego ejecutar:
$ obmenu-generator -s -c
