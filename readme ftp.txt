Primeramente hacemos una ctualizacion general del sistema mediante los 2 comandos:

    sudo apt-get update
    sudo apt-get upgrade

Despues de actualizar el sistema para tenerlo todo correctamente tendremos que ejecutar
el siguiente comando para la instalacion del servidor proFTP

    sudo apt-get install proftpd

Una vez ejecutado el comando se empezará a descargar y una vz termine se nos habrá
creado un nuevo archivo a cual accederemos mediante

    sudo nano /etc/proftpd/proftpd.conf

En este documento cambiaremos los parametros necesarios para conseguir todos los objetivos
que se nos pedian en la practica. Entre ellos algunos de los parametros que deberemos cambiar
son los puertos pasivos, los ajustes para la sesion de anonimo, entre otros

Por ultimo para la creacion de los 2 usuariosque nos piden lo haremos mediante

    sudo useradd user1
    sudo passwd user1
    sudo useradd user2
    sudo passwd user2
