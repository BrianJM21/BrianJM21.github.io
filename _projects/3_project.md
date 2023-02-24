---
layout: page
title: BitacorApp
description: Aplicación de geolocalización para el registro de incidencias.
img: assets/img/BitacorAppLogo.png
importance: 3
category: Aplicaciones iOS
---

**BitacorApp** fue el tercer proyecto en el que trabajé en el taller presencial de **Academia iOS - OGUM**. Además de ser un proyecto que incorpora elementos del desarrollo de iOS con cierto grado de complejidad como lo es el uso del **UIMapKit** y la arquitectura **MVVM**, la gran relevancia de este proyecto fue el **trabajo en equipo** con otros desarrolladores, los cuales **acredito debidamente en la documentación localizada en el repositorio remoto del proyecto**. Cabe mencionar que también se elaboró una **presentación profesional** y el proyecto se **documentó completamente en inglés**. Si bien la aplicación tiene varias **áreas de mejora**, la considero muy relevante e importante debido a la práctica y experiencia que obtuve trabajando en equipo, así como utilizando en un caso **real y práctico** el controlador de versiones **Git** y **GitHub**.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/BitacorApp1.png" title="Home Screen" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/BitacorApp2.png" title="Detail Screen" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/BitacorApp3.png" title="Log Screen" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <b>Izquierda:</b> <i>Pantalla de Inicio.</i>
    <b>Centro:</b> <i>Pantalla de edición de incidencias.</i>
    <b>Derecha:</b> <i>Pantalla de edición de la bitácora.</i>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/BitacorAppGIF.gif" title="gif image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Muestra de la aplicación.
</div>

## Características

- **Aplicación de geolocalización** para el registro de incidencias.
- Diseño de arquitectura **MVVM**.
- **Crea y edita** marcas (notaciones) sobre un mapa del **UIMapKit**.
- Cada marca del mapa integra **sus coordenadas, título, descripción y una bitácora de seguimiento**.
- Persistencia de datos locales con **CoreData** para las marcas en el mapa.
- La vista principal incorpora una **vista flotante con animación** para mostar los detalles de la marca del mapa seleccionada.
- Pantalla de detalles desde donde se puede editar el **título, descripción y alimentar la bitácora de seguimiento de la incidencia**.
- Implementa un patrón de diseño de **Observable** con propiedades publicadas para comunicación entre las vistas y el modelo de datos por medio de los vista-modelo.

## Tecnologías/Frameworks

- **UIKit:** Para el diseño de la interfaz de usuario.
- **UIMapKit:** Para el despliegue del mapa y las marcas sobre el mismo.
- **CoreData:** Para la persistencia de datos de las marcas sobre el mapa y la bitácora.
- **Published:** Para la observabilidad del modelo de datos y su presentación en las vistas.