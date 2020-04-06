---
title: Diseño de un sistema de gestión de archivos escalable y resiliente.
speakers:
  - Daniel Valencia Backhoff
tracks:
  - Arquitectura & DevOps
day_num: 2
time_start: 2020-04-21T23:00:00.000Z
time_end: 2020-04-21T23:50:00.000Z
---
<!--StartFragment-->

Cuando un desarrollador piensa en implementar funcionalidad para subir archivos a un servidor lo primero que viene a la mente es una forma HTML multipart. Pero, has intentado subir un archivo de 1GB utilizando un form ? Y uno de 40GB ? Resulta ser que el problema no es tan sencillo considerando la memoria limitada de un navegador y que las conexiones a internet suelen ser lentas y poco confiables.\
\
En esta charla hablaré de los retos al diseñar la arquitectura para subir archivos a nuestra plataforma en HELIX (https://www.helixre.com), que funciona con archivos de prácticamente cualquier tamaño, bajo condiciones de internet poco idóneas, y aprovechando las facilidades que te da la nube.

<!--EndFragment-->