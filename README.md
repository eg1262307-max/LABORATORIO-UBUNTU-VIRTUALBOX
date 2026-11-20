# LABORATORIO-UBUNTU-VIRTUALBOX
Laboratorio de instalación y configuración de Ubuntu en VirtualBox
# Laboratorio Ubuntu en VirtualBox

## 1. Configuración de red

Se seleccionó el modo **Red Interna (Internal Network)** para configurar el aislamiento de la máquina virtual. Esta modalidad permite la comunicación entre máquinas virtuales conectadas a la misma red interna, pero impide que tengan acceso directo a la red física o a Internet.

Se eligió esta configuración porque el objetivo de la prueba inicial es trabajar en un entorno aislado y controlado, reduciendo la exposición del sistema invitado a redes externas.

No se utilizó el modo **Puente (Bridged)** porque este conecta la máquina virtual directamente a la red física, haciendo que pueda comunicarse con otros dispositivos de dicha red y aumentando su exposición. Para este laboratorio no es necesario ese nivel de conectividad.

## 2. Instantánea del sistema

Se creó una instantánea denominada **Instalación Base Limpia**, que conserva el estado inicial de Ubuntu 24.04 con las actualizaciones y Guest Additions instaladas, y la configuración de red establecida en Red Interna.

Esta instantánea permite restaurar el entorno a su estado inicial si se producen errores o cambios durante las próximas pruebas.

## 3. Evidencias

- Captura 1: Configuración de red de VirtualBox mostrando el modo Red Interna.
- Captura 2: Administrador de instantáneas mostrando Instalación Base Limpia.
