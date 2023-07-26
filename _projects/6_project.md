---
layout: page
title: La Hacienda App
description: Aplicación para pedir agua a domicilio.
img: assets/img/LaHaciendaLOGO.jpg
importance: 1
category: Aplicaciones iOS
---

**La Hacienda** es una aplicación que sirve para **hacer pedidos de agua potable a domicilio.** El nombre lo toma de una **purificadora real** ubicada en el Edo. de México, cuyo **dueño y amigo mío me pidio desarrollar una App para dicho negocio.** Este proyecto, ha sido uno de mis más grandes logros como Freelance a la fecha, **utiliza una arquitectura MVVM, patrones de delegamiento, observabilidad, inyección de dependiencias, adaptabilidad y segregación de interfaces.** También incorpora un **servicio de BackEnd de Google-FireBase para la autenticación y manejo de base de datos sincronizada en tiempo real.**


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/LaHacienda1.png" title="Login" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/LaHacienda2.png" title="Sign Up" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/LaHacienda3.png" title="Order" class="img-fluid rounded z-depth-1" %}
    </div>
<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/LaHacienda4.png" title="Home" class="img-fluid rounded z-depth-1" %}
    </div>
<div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/LaHacienda5.png" title="Map" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <b>Izquierda:</b> <i>Pantallas de Inicio de Sesión y Registro.</i>
    <b>Centro:</b> <i>Pantallas de Ordenar e Inicio.</i>
    <b>Derecha:</b> <i>Pantalla del Mapa.</i>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/LaHaciendaGIF.gif" title="gif image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Muestra de la aplicación.
</div>

## Características

- Aplicación que permite hacer pedidos de agua potable a domicilio.
- Diseño de arquitectura **MVVM** que incorpora **patrones de observabilidad, delegamiento, adaptabilidad y segregación de interfaces.**
- Servicio de **autenticación a través de Google FireBase Auth.**
- Servicio de **base de datos con sincronización en tiempo real a través de Google FireStore.**
- Uso del API nativo **MapKit para buscar y seleccionar marcaciones en mapas.**
- El usuario puede **registrarse, iniciar sesión, mantener esa sesión abierta al cierre y apertura de la App, y cerrar sesión.**
- El usuario puede **ordenar agua, chatear con el proveedor, monitorear el estado de la orden, consultar su historial de pedidos y modificar sus datos de contacto, todo con actualizaciones en tiempo real.**
- Uso del API **UIKit para la interfaz gráfica,** así como **animaciones y layouts dinámicos y responsivos.**

## Tecnologías/Frameworks

- **UIKit:** Para el diseño de la interfaz de usuario.
- **Google FireBase:** Para el servicio de autenticación y base de datos.
- **Combine:** Para la implementación de observadores.
- **MVVM:** Como arquitectura de diseño principal.
- **MapKit:** Para la generación de mapas y direcciones.
- **UIView.animation:** Para las animaciones de algunos elementos de la interfaz de usuario.