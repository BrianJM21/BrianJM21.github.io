---
layout: page
title: Notes App
description: Aplicación utilitaria para crear y gestionar notas personales.
img: assets/img/NotesAppLogo.png
importance: 2
category: Aplicaciones iOS
---

**Notes App** es una aplicación de *funcionalidad básica* pero de **diseño limpio, claro y robusto**. Mi principal **objetivo** al desarrollarla fue implementar una **arquitectura MVC claramente segmentada** haciendo de esta, una aplicación de fácil mantenimiento. También me enfoqué en dar una **buena experiencia de usuario**, al implementar tablas con animaciones, navegación a través de una TabBar y vistas ágiles a prueba de errores. Mi **motivación** al trabajar en este proyecto fue la de implementar diferentes **técnicas de persistencia de datos locales**, así como madurar **habilidades y buenas prácticas de programación** en Swift.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/NotesApp1.png" title="Home Screen" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/NotesApp2.png" title="Add Screen" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/NotesApp3.png" title="Settings Screen" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <b>Izquierda:</b> <i>Pantalla de Inicio.</i>
    <b>Centro:</b> <i>Pantalla de creación.</i>
    <b>Derecha:</b> <i>Pantalla de Configuración.</i>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/NotesAppGIF.gif" title="gif image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Muestra de la aplicación.
</div>

## Características

- **Aplicación utilitaria** para crear y gestionar notas personales.
- Diseño de arquitectura **MVC**.
- **Crea, edita y elimina** notas de texto personales.
- Cada nota tiene un **título** y un **cuerpo**.
- Permite **personalizar las vistas** con una **configuración de usuario persistente**.
- Persistencia de datos locales con **UserDefaults** para la configuración de usuario y **FileManager** para las notas.
- Gestión del modelo de datos de las Notas con un **UITableViewDiffableDataSource**, el cual ofrece una mejor experiencia de usuario.
- Navegación entre las notas y la configuración de usuario con un **UITabBar**.
- Navegación y transferencia de datos entre las vistas de las Notas por medio de **Segues**.
- Implementa un patrón de diseño de **Delegamiento**.

## Tecnologías/Frameworks

- **UIKit:** Para el diseño de la interfaz de usuario.
- **Protocolos/Delegamiento:** Para las operaciones sobre el modelo de datos.
- **UserDefaults:** Para la persistencia de datos de la configuraicón de usuario.
- **FileManager:** Para la persistencia de datos de las notas.
- **UITableViewDiffableDataSource** Para la presentación del modelo de datos (notas).