---
layout: page
title: History Trivia
description: Juego de Trivia con temática histórica.
img: assets/img/HistoryTriviaLogo.jpg
importance: 1
category: Aplicaciones iOS
---

**History Trivia** ha sido uno de mis primeros proyectos como *desarrollador iOS* con tan solo **2 meses** de estudio en el tema. Mi principal **motivación** al crearlo fue maduarar mis *conocimientos* y *habilidades* como desarrollador iOS a través de la **implementación** o práctica. Si bien la idea original no es mía, sino que formó parte del temario de estudio del curso *iOS Developer* de la plataforma de aprendizaje en línea **Codecademy**, implementé funcionalidades y características propias que la hacen parte de mi portafolio personal de aplicaciones.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/HistoryTrivia1.png" title="Home Screen" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/HistoryTrivia2.png" title="Game Screen" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/HistoryTrivia3.png" title="Score Screen" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <b>Izquierda:</b> <i>Pantalla de Inicio.</i>    <b>Centro:</b> <i>Pantalla del Juego.</i>.   <b>Derecha:</b> <i>Pantalla de Puntaje Final.</i>
</div>

## Características

- **Juego de Trivia** con temática histórica.
- Diseño de arquitectura **MVVM**.
- Tiene **10 preguntas precargadas** por defecto.
- Permite agregar **preguntas personalizadas**.
- Persistencia de datos locales con **Core Data** para las preguntas personalizadas.
- Dos modos de juego disponibles.
- **Juego Completo**: Usa todas las preguntas disponibles en la base de datos.
- **Juego Rápido**: Usa el número de preguntas especificadas por el jugador.
- Cada ronda carga las preguntas de manera aleatoria.
- Implementa patrones de diseño **Observable** y **Singleton**.

## Tecnologías/Frameworks

- **UIKit:** Para el diseño de la interfaz de usuario.
- **Combine:** Para la observabilidad de objetos como parte de un patrón de diseño Observable.
- **CoreData:** Para la persistencia de datos en las preguntas personalizadas.