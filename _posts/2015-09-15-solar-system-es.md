---
layout: post
title: Simulación del Sistema Solar
excerpt_separator: <!--more-->
categories:
  - Proyectos
tags:
  - Unity
  - C Sharp
  - Universidad del Estado de Michigan  
ref: solar-system
lang: es
---

Este es probablemente el primer proyecto que llevé a cabo con Unity, una especie de simulación del sistema solar (bueno, algo así!).
En cualquier caso, muestra todos los planetas del sistema solar moviéndose por la pantalla.

<!--more-->

Fue un ejercicio de los cursos de la Universidad del Estado de Michigan que tomé sobre Desarrollo de Juegos.

Durante este proyecto aprendí sobre algunos conceptos del motor de videojuegos, tales como:
* Crear materiales
* Trabajar con una cámara adicional para crear un mini-mapa
* Temas de audio básicos
* Iluminación básica
* Hacer que la cámara siga a los objetos de juego

Con este proyecto no intentaba buscar realismo en ningún sentido, y ciertamente no intenta ser una simulación:
Sería difícil modelar las órbitas con precisión, y sólo podría verse un sol de enorme tamaño si
las proporciones y distancias entre los diferentes planetas se acercasen a la realidad.

Es posible jugar con una build WebGL de este proyecto [aquí](/assets/webgl/solar-system){:target="_blank"}.

## Controles
Haz click en cualquiera de los planetas, ya sea en la escena principal o en el mini-mapa, para que la cámara principal siga su trayectoria.
