---
layout: post
title: Super Sparty Bros
excerpt_separator: <!--more-->
categories:
  - Proyectos
tags:
  - Unity
  - C Sharp
  - Videojuegos
  - Universidad del Estado de Michigan
ref: super-sparty-bros
lang: es
---

Super Sparty Bros es una demo de juego de plataformas 2D, en la que hay que conseguir un objeto de "victoria" para poder pasarse cada nivel.
Con ese objetivo, deberás esquivar a una serie de enemigos a los que podrás aturdir saltando encima suyo.

<!--more-->

Este proyecto fue otra de las entregas que presenté durante el transcurso de los cursos de la Universidad del Estado de Michigan sobre Desarrollo de Videojuegos.
Esta era la primera ocasión en la que desarrollaba un proyecto en Unity para multi-plataforma.

Durante este proyecto aprendí sobre algunos conceptos del motor de videojuegos, tales como:
* Trabajar con sprites y físicas 2D
* Crear y controlar animaciones 2D
* Implementar mecánicas típicas de plataformas 2D
* Gestión del input multi-plataforma
* Guadar el estado de juego a través de Player Prefs
* Parallax scrolling
* Efectos de imagen (posteriormente los adapté para utilizar la nueva pila de post-procesamiento)

Puedes jugar con una build WebGL de este proyecto desde [aquí](/assets/webgl/super-sparty-bros){:target="_blank"}.
Hay otras builds disponibles en el [repositorio](https://github.com/azarrias/super-sparty-bros){:target="_blank"} del proyecto.

## Controles

Acción     | PC (ratón y teclado)        | PC (Mando tipo Xbox) | Móvil
---------- | --------------------------- | -------------------- | ------
Movimiento | WASD / Teclas de dirección  | Stick analógico      | Stick analógico virtual
Salto      | Barra espaciadora           | X                    | Pulsar el lado derecho de la pantalla
