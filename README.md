Repositorio Taller Servidores Linux
=========

En este repositorio encontrarán un playbook de Ansible. Dicho playbook instalará los paquetes referentes a Apache, generará un VirtualHost y un balanceador de carga.

Requirements
------------

Para la correcta ejecución de este playbook es necesario tener instalado sistemas operativos de la familia Debian o bien Redhat, se recomienda utilizar Ubuntu y Centos.

Role Variables
--------------

Las únicas variables a utilizar se encuentran en el archivo loadbalancer_vars.yml, las cuales hacen referencia al archivo del balanceador de carga que se encuentra en la carpeta templates.

Dependencies
------------

El playbook hace referencia a dos grandes roles de las dos familias que mencionamos anteriormente, dentro de cada rol en la carpeta tasks es donde se encuentran las tareas para la realización del playbook.


License
-------

BSD

Author Information
------------------

Creado por Lucas Lanza para la Universidad ORT.
