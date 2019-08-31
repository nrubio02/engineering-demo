# engineering-demo
Repositorio para prueba de concepto de configuracion de flujo de Integracion Continua/Despliegue Continuo (CI/CD), y snippets de codigo para observar dicho flujo en accion 

## Sobre la documentación
La documentación que se reuna en la wiki de éste repositorio se creará pincipalmente en español, sin embargo, se hará referencia a otros recursos que se encuentran principalmente en inglés, asi como las nomenclaturas que se usen dentro de los archivos de configuración y de código también se encontrarán en inglés.

Toda la documentación se recopilará en la [wiki del repositorio](https://github.com/nrubio02/engineering-demo/wiki/Inicio).

## Plataforma de prueba
Los ejemplos aqui descritos se ejecutarán sobre el siguiente sistema:

- Máquina virtual Virtualbox 6 con CentOS 7.6 como SO huésped 
  - 4GB de RAM
  - 20GB de Almacenamiento con asignación dinámica
  - Interfaz gráfica no instalada
  - Adaptador de red NAT (para acceso a internet) y Host-only (para accesso via SSH al huésped desde el anfitrión)

La preparación de la máquina virtual está fuera del alcance de éste repositorio, sin embargo comparto links que utilice como guía durante el proceso:

- [Instalación de VirtualBox Guest Additions](https://www.if-not-true-then-false.com/2010/install-virtualbox-guest-additions-on-fedora-centos-red-hat-rhel/)
- [Configuración de red Host-only](https://mikesmithers.wordpress.com/2018/11/17/virtualbox-configuring-a-host-only-network/)

Personalmente realice pasos adicionales a los mencionados en ambos enlaces para llegar a la configuración deseada y que en su momento no documenté al no ser parte del ejercicio que deseo ilustrar. Posteriormente recrearé el proceso y actualizaré la documentación, sin embargo no es la prioridad del ejercicio en éste momento.