# Red Hat. Principales hitos
- Red Hat Inc. Creada en 1993/1994 (Bob Young y Marc Erwing)
- 1994: Se publica Red Hat Linux (RHL)
- 1999: Sale en bolsa.
- 2003: Se abandona RHL y surge RHEL (Red Hat Entrerprise Linux).
- 2003: Aparece Fedora (comunidad apoyada por RH). Se necesita estar 
- 2004: Aparece CentOS (proyecto independiente). Es un clon del Enterprise, antiguos usuarios de Red Hat Linux por la creación de Fedora, limpiando todo el software propio de Red Hat. 
- 2014: Red Hat acuerda apoyar a CentosOS. Antes estaba en contra, hasta que se dieron cuenta de que les beneficiaba.
- 2019: IBM anuncia la compra de Red Hat en octubre de 2018.

## Modelo de negocio
- Inicialmente software Unix y Linux.
- Se centra en soluciones de software libre.
- Siempre utilizando el término "open source".
- Ofrece soporte, consultoría, formación y certificación en sus tecnologías.
- Una de las empresas que más contribuyen en proyectos de software libre.
- Trabaja típicamente con grandes clientes.


## Principales adquisiciones
- Cygnus
- Sistina
- JBoss
- Qumranet
- Ansible
- etc...

## Principales productos
> Sistemas:
- RHEL (Distribución principal)
- REHV (KVM, oVirt, ...)
- RHIMI (ipa)
- Almacenamiento: Ceph y Gluster

> Clud:
- Cloudforms
- OpenStack
- OpenShift

> JBoss

Red Hat se dedica a determiandos sectores de la informática que a ellos les interesa. 


### Fedora
- Principal prodcuto del "Fedora Project"
- Comunidad soportada por Red Hat
- Se publica cada 6 meses (aproximadamente) y se soporta durante 13 meses  más.
- No existe versión LTS
- Incluye software más actualizado wue RHEL o CentOS
- Última versión estable (Nov 2019): Fedora 31


## Principales difernecias técnicas con Debian
- Paquetes rpm en lugar de deb, lo que significa que los paquetes no son compatibles y que los modelos de paquetes no son iguales.
- Gestor de paquetes con rpm en lugar de dpkg. 
- Gestión de repositios con yum?, ya no se usa, y dnf en lugar de apt.
- Repositorios oficiales con muchos menos paquetes.
- Soporte de hasta 10 años.
- Solo son accesibles los paquetes de las versiones estables. 
- Utiliza anaconda en lugar de debian-installer.
- SELinux activado por defecto. SELinux es un mecanismo de seguridad adicional que a su vez hace que modificaciones no estandar no sean accesibles inmediatamente. 
- Utilización de firewalld. Es la envoltura de IP table.
- Directorio /etc/sysconfig.

