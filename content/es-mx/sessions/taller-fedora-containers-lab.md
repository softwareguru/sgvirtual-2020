---
title: "Taller: Fedora Containers Lab"
speakers:
  - Alex Callejas
tracks:
  - Tendencias
day_num: 5
time_start: 2020-04-24T23:00:00.000Z
time_end: 2020-04-25T01:30:00.000Z
video: "https://crowdcast.io/e/sgvirtual/47"

---
En este taller vamos a mostrar cómo crear y manejar contenedores desde cero.

Usando ejercicios sencillos, con skopeo, podman y buildah mostraremos cómo crear contenedores básicos basados en imagenes del registro fedora, hasta contenedores personalizados basados en Docker y posteriormente cómo usar estos contenedores para aprender los principios de Kubernetes.

### Requisitos
* Kernel con soporte para KVM (fedora, Debian, Arch, etc). Ver [más información](https://docs.fedoraproject.org/en-US/quick-docs/getting-started-with-virtualization/)
* Mínimo 5G de espacio en disco disponible.
* Tener instalados los siguientes paquetes: `qemu-kvm virt-manager virt-viewer libguestfs-tools virt-install genisoimage` 
* Descargar la imagen de [Fedora 31 Cloud Base](https://alt.fedoraproject.org/cloud/) (descargar "Cloud Base Image for Openstack").
