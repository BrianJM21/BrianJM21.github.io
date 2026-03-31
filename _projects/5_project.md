---
layout: page
title: Random Users Generator
description: Aplicación que se conecta a la API de randomuser.me y presenta los resultados en distintos formatos.
img: assets/img/RUGLogo.png
importance: 1
category: Aplicaciones iOS
---

**Random Users Generator** es una aplicación que se comunica con la **API** de *randomuser.me* para peticionar, recibir y presentar un número determiado de usuarios aleatorios. La presentación de la información recibida, lo hace de **tres** maneras diferentes: **Pretty JSON, lista simple, y una colección de imágenes y etiquetas.** Además, incorpora elementos dinámicos de la interfaz de usuario, a través de **animaciones y acondicionamiento en tiempo de ejecución**. El principal **objetivo y motivación** de la aplicación, es el **uso de peticiones HTTP, manejo de la información recibida, y control de hilos secundarios (para las peticiones remotas) e hilo principal (para la interfaz de usuario).**


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/RUG1.png" title="Home Screen" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/RUG2.png" title="List Screen" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/RUG3.png" title="Details Screen" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <b>Izquierda:</b> <i>Pantalla de Inicio.</i>
    <b>Centro:</b> <i>Pantalla de Usuarios Generados en formato Colección.</i>
    <b>Derecha:</b> <i>Pantalla de Detalles.</i>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/RUGGIF.gif" title="gif image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Muestra de la aplicación.
</div>

## Características

- Aplicación que se conecta a la **API** de *randomuser.me* y presenta los resultados en distintos formatos.
- Diseño de arquitectura **MVC desacoplada** (controlador y UI).
- El usuario de la aplicación, determina la cantidad de usuarios aleatorios a generar.
- Tres maneras de presentar la información recibida: **Pretty JSON, lista simple, y una colección de imágenes y etiquetas.**
- Diseño de la interfaz dinámica y reactiva a los procesos que se llevan a cabo en los hilos secundarios.
- Uso del framework nativo **async/await** para las peticiones HTTP.
- Incorporación de **Pruebas Unitarias** para el **módulo que realiza las peticiones HTTP.**
- Implementa un patrón de diseño de **Inyección de Dependencias**.

## Tecnologías/Frameworks

- **UIKit:** Para el diseño de la interfaz de usuario.
- **Inyección de Dependencias:** Para la comunicación de objetos entre vistas.
- **Async/Await:** Para las peticiones HTTP.
- **XCTest:** Para las pruebas unitarias del módulo que se comunica con la API.
- **randomuser.me:** Para la generación de usuarios aleatorios.
- **UIView.animation:** Para las animaciones de algunos elementos de la interfaz de usuario.