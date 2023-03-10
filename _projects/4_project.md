---
layout: page
title: ToDo App
description: Aplicación para gestionar ToDos localmente y con servicio remoto en la nube.
img: assets/img/ToDoAppLogo.png
importance: 1
category: Aplicaciones iOS
---

**ToDo App** ha sido, a la fecha en que escribo esto, un **gran logro en mi carrera como desarrollador iOS**, al ser mi primera aplicación que incorpora **servicios de almacenamiento y sincronización en la nube** a través de **MongoDB Atlas** y el **SDK de Realm para Swift**. La **motivación** de este proyecto fue la de **entender, aplicar y como resultado madurar los conceptos de persistencia de datos locales, remotos y la sincronización de ambos**; con miras a desarrollar posteriormente aplicaciones más complejas utilizando estos principios y tecnologías. Los **objetivos fueron crear una aplicación básica** en el mundo del desarrollo de software como lo es una **App de ToDos, con la característica de poder sincronizar ToDos de manera local y remota por medio de un servicio en la nube, apoyandome a su vez de un servicio de autenticación de usuarios**, creando así una **experiencia más personalizada y útil** al usuario.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ToDoApp1.png" title="Home Screen" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ToDoApp2.png" title="Edit Screen" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ToDoApp3.png" title="Login/SignUp Screen" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <b>Izquierda:</b> <i>Pantalla de Inicio.</i>
    <b>Centro:</b> <i>Pantalla de Edición.</i>
    <b>Derecha:</b> <i>Pantalla de Login/SignUp.</i>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ToDoAppGIF.gif" title="gif image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Muestra de la aplicación.
</div>

## Características

- **Aplicación utilitaria** para gestionar **ToDos.**
- Persistencia de datos locales y sincronización con Base de Datos remota con **SDK de Realm para Swift** para los ToDos y **UserDefaults** para el nombre de usuario.
- Servicio de almacenamiento en la nube, autenticación de usuarios (user - password) y administración de Base de Datos con **MongoDB Atlas.**
- Permite crear ToDos **locales** y/o **asociados a una cuenta de usuario.**
- Permite **importar ToDos locales a una cuenta de usuario para su persistencia en la nube.**
- Permite **conservar ToDos asociados a una cuenta de usuario como copias locales en el dispositivo.**
- Permite trabajar en modo **"OffLine"** con los ToDos asociados a una cuenta de usuario, los cuales se **sincronizan con la Base de Datos remota una vez se conecta a Internet el dispositivo.**
- Manejo de **funciones y tareas asíncronas (concurrencia).**
- Implementa patrones de diseño **Observable** y **Delegamiento**.
- **Interfaz de usuario creada programáticamente.**
- Uso de **UITableViewDiffableDataSource** para una mejor experiencia de usuario al visualizar y manejar los ToDos.

## Tecnologías/Frameworks

- **UIKit:** Para el diseño de la interfaz de usuario.
- **RealmSwift:** Para la persistencia de datos locales (toDos) en una DB, observabilidad de los objetos insertos en la DB local y sincronización con los servicios en la nube de MongoDB Atlas.
- **MondgoDB Atlas:** Para el servicio de almacenamiento en la nube, autenticación de usuarios y manejo de DB remota.
- **UserDefaults:** Para la persistencia de datos locales (nombre de usuario).
- **async/await y completionHandlers:** Para el manejo de funciones y rutinas asíncronas.
- **Delegamiento (Protocolos) e Inyección de Dependencia:** Para la comunicación entre vistas.