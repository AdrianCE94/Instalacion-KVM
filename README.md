# Instalacion-KVM


![kvm](descarga-1.png)

Instalación de KVM en maquina virtualizada , vamos a utilizar la maquina preparada , puedes consultar como preparar la maquina en el siguiente enlace 

[Preparar maquina virtualizada](https://github.com/AdrianCE94/maquinaDebian12)


# Contenido
- [Instalacion-KVM](#instalacion-kvm)
- [Contenido](#contenido)
- [1. ¿Qué es KVM?](#1-qué-es-kvm)
- [2. Ventajas de KVM e inconvenientes](#2-ventajas-de-kvm-e-inconvenientes)
- [3. qemu, libvirt, libvirtd, virsh y virt-manager](#3-qemu-libvirt-libvirtd-virsh-y-virt-manager)
- [4. Requirements Hardware \& Software](#4-requirements-hardware--software)
- [5. Instalación de KVM en Debian 12](#5-instalación-de-kvm-en-debian-12)
---
# 1. ¿Qué es KVM?

KVM (Kernel Virtual Machine) es una arquitectura de virtualización complet de software libre.

Se presenta como una alternativa a sistemas de virtualización propietarios como Hyper-V y VMware. 

KVM tiene dos componentes esenciales que son:
- **El módulo del kernel kvm.ko** que proporciona la infraestructura de virtualización del núcleo.
- **QEMU** que proporciona la emulación de hardware.

# 2. Ventajas de KVM e inconvenientes

| **Ventajas**                   | **Inconvenientes**              |
|--------------------------------|---------------------------------|
| Es software libre.             | Puede requerir conocimientos técnicos avanzados. |
| Mejora la eficiencia.          | Compatibilidad|
| Flexibilidad                   | Dependencia de hardware compatible. |
| Escalabilidad                  | Puede haber problemas de rendimiento en entornos muy grandes. |
| Seguridad                      | Necesidad de actualizaciones y mantenimiento regulares. |
| Facilidad de uso               | La documentación puede ser escasa o difícil de seguir. |

# 3. qemu, libvirt, libvirtd, virsh y virt-manager

- **QEMU** es un emulador de hardware y virtualizador de máquinas. Es el encargado de emular el hardware de la máquina virtual.
- **libvirt** es un toolkit para gestionar plataformas de virtualización 
- **libvirtd** es un demonio que actúa como servidor de libvirt.
- **virsh** es una interfaz de línea de comandos para gestionar máquinas virtuales.1
- **virt-manager** es una interfaz gráfica para gestionar máquinas virtuales.


# 4. Requirements Hardware & Software

- **Hardware**:
  - Procesador con soporte de virtualización (Intel VT-x o AMD-V).
  - 2 GB de RAM.
  - Disco suficiente para la instalación de los sistemas operativos.

- **Software**:
  - **Sistema operativo** Linux con el modulo KVM cargado.
  - **QEMU** instalado.
  - **libvirt y libvirtd** instalado.

# 5. Instalación de KVM en Debian 12	

