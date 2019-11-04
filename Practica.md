# Gestión de paquetes
1. Modifica la configuración de red de DHCP a estática

Para poder entrar con contraseña:
~~~
sudo /etc/ssh/sshd_config
~~~
Se modifica el parámetro PasswordAutentification? por 'yes'.

~~~
[centos@practicacentos ~]$ sudo nano /etc/sysconfig/network-scripts/ifcfg-eth0
~~~
~~~
# Created by cloud-init on instance boot automatically, do not edit.
#
BOOTPROTO=static
IPADDR="192.168.1.10"
NETMASK="255.255.255.0"
GATEWAY=192.168.1.1
DEVICE=eth0
HWADDR=fa:16:3e:08:8c:75
ONBOOT=yes
TYPE=Ethernet
USERCTL=no
~~~

~~~
sudo systemctl restart network
~~~


2. Actualiza el sistema a las versiones más recientes de los paquetes instalados
~~~
yum upgrade
~~~


3. Instala los repositorios adicionales EPEL y CentOSPlus

4. Instala el paquete que proporciona el programa dig, explicando los pasos que has dado para encontrarlo

5. Explica qué comando utilizarías para ver la información del paquete kernel instalado

6. Instala el repositorio adicional "elrepo" e instala el último núcleo disponible del mismo (4.3.X)

7. Busca las versiones disponibles para instalar del núcleo linux e instala la más nueva

8. Muestra el contenido del paquete del último núcleo instalado


