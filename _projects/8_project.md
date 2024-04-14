---
layout: page
title: Grimm Story Teller AI
description: App que te ayuda a generar cuentos e historias para niños en cuestión de segundos, con ayuda de la IA.
img: assets/img/GrimmLogo.png
importance: 2
category: Aplicaciones iOS
---

**Gimm: StoryTeller AI** es una aplicación que te ayuda a **generar cuentos e historias para niños en cuestión de segundos, con la ayuda de la IA.** Este proyecto está construido con **SwiftUI y una arquitectura MV**. Incorpora **el API de OpenAI chatGPT para la generación de cuentos.**


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Grimm1.png" title="Home" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Grimm2.png" title="Character creation" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Grimm3.png" title="Generated Tale" class="img-fluid rounded z-depth-1" %}
    </div>

</div>
<div class="caption">
    <b>Izquierda:</b> <i>Pantalla Principal.</i>
    <b>Centro:</b> <i>Creación de personajes.</i>
    <b>Derecha:</b> <i>Pantalla Generación de Cuento.</i>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/GrimmGIF.gif" title="gif image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Muestra de la aplicación.
</div>

## Características

- Aplicación que permite generar cuentos para niños.
- Diseño de arquitectura **MV.**
- Uso del API de openAI **ChatGPT.**
- El usuario puede especificar uno o más parámetros para la generación de un cuento para niños, entre los que se encuentra: temática, moraleja, número de parrafos o palabras, entre otros.
- El usuario puede pedir sugerencias para llenar los parámetros del cuento a generar.
- El usuario puede incluir o no, personajes en el cuento, especificando parámetros como: nombre, profesión, rol, entre otros.
- El usuario puede optar por dejar todos los parámetros vacíos y dejar que la IA genere un cuento aleatoriamente.
- El usuario puede almacenar un cuento si este fue de su agrado y lo quiere releer en el futuro.
- Uso del API **SwiftUI** para la interfaz de usuario.

## Tecnologías/Frameworks

- **SwiftUI:** Para el diseño de la interfaz de usuario.
- **OpenAI ChatGPT API:** Para la generación del cuento.
- **MV:** Como arquitectura de diseño principal.
- **AppStorage**: Como persistencia de datos locales para almacenar un cuento generado.