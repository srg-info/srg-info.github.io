---
layout: page
title: Proyectos
permalink: /proyectos/
---

## Aquí puedes ver los proyectos o trabajos realizados.
---
📌 Proyectos desarrollados en el ITZO: [Ver](ITSZO.md)
---
📌Proyectos desarrollados en el ICAIF: [Ver](ICAIF.md)
---
📌 Proyectos profesionales: [Ver](Profesionales.md)


<details>
<summary><strong>1. Automatizando tareas repetitivas con Python
En el mundo de la tecnología, muchas tareas rutinarias se pueden automatizar para ahorrar tiempo y evitar errores.
En este mini proyecto, utilicé Python para renombrar archivos automáticamente en una carpeta, agregando la fecha al nombre de cada archivo. Es un ejemplo básico, pero muy útil para empezar a usar scripts en el trabajo diario.</strong></summary>
import os
from datetime import datetime

fecha = datetime.now().strftime("%Y%m%d")
carpeta = "C:/archivos"

for nombre in os.listdir(carpeta):
    origen = os.path.join(carpeta, nombre)
    destino = os.path.join(carpeta, f"{fecha}_{nombre}")
    os.rename(origen, destino)
--
Esto permite procesar documentos, imágenes o logs automáticamente con solo ejecutar el script
</details>
