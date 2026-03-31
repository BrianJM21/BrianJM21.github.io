---
layout: page
title: Budgit
description: App que te ayuda a controlar y monitorial tus ingresos y egresos para una mejor gestión de tus finanzas personales.
img: assets/img/BudgitLogo.png
importance: 2
category: Aplicaciones iOS
---

**Budgit** es una aplicación que te ayuda a **gestionar cuentas y presupuestos** así como **entradas y salidas de dinero** para eficientar la gestión de tus finanzas personales. Este proyecto está construido con **SwiftUI y una arquitectura MV**. Incorpora **SwiftData y es compatible con el system design de Liquid Glass de Apple**


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Budgit1.png" title="Home" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Budgit2.png" title="Character creation" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Budgit3.png" title="Generated Tale" class="img-fluid rounded z-depth-1" %}
    </div>

</div>
<div class="caption">
    <b>Izquierda:</b> <i>Pantalla Principal.</i>
    <b>Centro:</b> <i>Creación de Transacciones.</i>
    <b>Derecha:</b> <i>Historial de movimientos.</i>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/BudgitGIF.gif" title="gif image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Muestra de la aplicación.
</div>

## Características

- Aplicación que permite gestionar cuentas, presupuestos y movimientos de dinero entre ellas.
- El usuario puede crear y eliminar cuentas, así como personalizarlas con un nombre y saldo inicial.
- El usuario puede crear y eliminar presupuestos, así como personalizarlos con un nombre, presupuesto total, presupuesto inicial, periodicidad y comportamiento en el tiempo.
- El usuario puede crear movimientos de ingreso y egreso de dinero, afectado las cuentas y presupuestos disponibles. También puede personalizar los movimientos asignado un nombre, descripción y fecha.
- El usuario puede visualizar las cuentas y presupuestos activos así como el saldo al día.
- Al seleccionar una cuenta o presupuesto, el usuario puede visualizar el historial de movimientos ordenados por fecha.

## Tecnologías/Frameworks

- **SwiftUI:** Para el diseño de la interfaz de usuario.
- **MV:** Como arquitectura de diseño principal.
- **SwiftData**: Como persistencia de datos locales para almacenar cuentas, presupuestos y movimientos.
- Localización de textos para una interfaz español/inglés.