---
layout: page
title: iCast
description: App para transmitir archivos multimedia locales y remotos a un dispositivo Google Chromecast.
img: assets/img/iCastLOGO.png
importance: 1
category: Aplicaciones iOS
---

**iCast** es una aplicación que sirve para **transmitir archivos multimedia locales y remotos a un dispositivo Google Chromecast** disponible en la misma red local WIFI a la que se conecta el iPhone. La App utiliza el servidor remoto de **Google Cloud Storage** para **subir temporalmente los archivos multimedia locales seleccionados desde la Photolibrary** del iPhone y lo transmite al dispositivo ChromeCast, también es posible **transmitir una url de la web** copiando y pegando dicha url en la App. Finalmente la App tiene una **funcionalidad experimental para transmitir la pantalla del iPhone al dispositivo ChromeCast**, sin embargo esta está en desarrollo y **NO** se recomienda utilizarla.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/iCast1.png" title="Home" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/iCast2.png" title="Full Screen Media Controls" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/iCast3.png" title="Mini Screen Media Controls" class="img-fluid rounded z-depth-1" %}
    </div>

</div>
<div class="caption">
    <b>Izquierda:</b> <i>Pantallas Principal.</i>
    <b>Centro:</b> <i>Pantallas de Transmisión.</i>
    <b>Derecha:</b> <i>Pantalla Principal con MiniControles de Transmisión.</i>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/iCastGIF.mp4" title="gif image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Muestra de la aplicación.
</div>

## Características

- Aplicación para transmitir archivos multimedia locales y remotos a un dispositivo **Google Cast.**
- Diseño de arquitectura **MVC.**
- El usuario puede acceder a sus archivos multimedia locales desde la **PhotoLibrary** de su iPhone.
- Servicio de almacenamiento temporal de archivos multimedia locales en **Google Firebase Cloud Storage.**
- Implementación del **SDK GoogleCast** para la conexión y transmisión de archivos multimedia.
- Uso del API **ReplayKit** para la función experimental de grabar la pantalla del iPhone.
- Uso del API **UIKit para la interfaz gráfica.**

## Tecnologías/Frameworks

- **UIKit:** Para el diseño de la interfaz de usuario.
- **Google FireBase:** Para el servicio de alojamiento temporal de archivos locales.
- **MVX:** Como arquitectura de diseño principal.
- **Google Cast:** Para la conexión y transmisión a los dispositivos ChromeCast.
- **ReplayKit:** Para el servicio de grabación de pantalla.