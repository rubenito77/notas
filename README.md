# Comprimir y descomprimir

~~~
Comprimir y descomprimir
------------------------
 
Archivos .tar.gz:
Comprimir: tar -czvf empaquetado.tar.gz /carpeta/a/empaquetar/
Descomprimir: tar -xzvf archivo.tar.gz

Archivos .tar:
Empaquetar: tar -cvf paquete.tar /dir/a/comprimir/
Desempaquetar: tar -xvf paquete.tar

Archivos .gz:
Comprimir: gzip -9 index.php
Descomprimir: gzip -d index.php.gz

Archivos .zip:
Comprimir: zip archivo.zip carpeta
Descomprimir: unzip archivo.zip


Copiar clave publica SSH a un Server Linux | SCP y ssh-copy-id
--------------------------------------------------------------
https://eltallerdelbit.com/copiar-clave-publica-ssh-scp-ssh-copy-id/

Ansible tutorial
----------------
https://www.educba.com/ansible-ping/

https://www.linuxtechi.com/use-debug-module-ansible-playbook/


Cambiar entre versiones de Java
-------------------------------
Cambiar versión por defecto de Java
Ejecuta la siguiente línea de comando en un terminal:

sudo update-alternatives --config java
Esto mostrará las versiones disponibles en el sistema, algo semejante a la siguiente tabla:

There are 2 choices for the alternative java (providing /usr/bin/java).

  Selection    Path                                            Priority   Status
------------------------------------------------------------
* 0            /usr/lib/jvm/java-11-openjdk-amd64/bin/java      1111      auto mode
  1            /usr/lib/jvm/java-8-openjdk-amd64/jre/bin/java   1081      manual mode

Press <enter> to keep the current choice[*], or type selection number: 0

Como se puede ver, el comando se queda esperando para seleccionar la versión que se desea elegir por defecto.
De esta manera y con un solo y sencillo comando pueden cambiar la versión de Java.
~~~
