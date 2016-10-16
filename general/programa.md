---
title: Programación PVLI (2016/2017) - preliminar
author: Belén Albeza, Carlos León, Salvador de la Puente, Ismael Sagredo
date: 13/10/2016
vim: spelllang=es
...

# 26-30 de septiembre

Tema 1: Programación de aplicaciones en HTML5

- 26/9 (Ismael y Carlos)
    - Presentación de la asignatura (objetivos, enfoque, criterios de
      evaluación...)
    - Introducción a lenguajes interpretados (Javascript)
- 27/9 (Carlos)
    - JavaScript: introducción a la sintaxis
    - Toolset: `git`, `node.js`, `npm`, `gulp`, `yo`, `http-server`, `browserify`, `Chrome`, `Firefox`, editor de texto
- 30/9 (Belén y Salva)
    - Charla inicial: Introducción a las Tecnologías de Videojuegos en Internet

# 03-07 de octubre 

Tema 2: Javascript (I)

- 03/10 (Salva)
    - Programación orientada a objetos con JavaScript
    - Datos primitivos
    - La función como tipo de datos
    - Constructores y prototipos
- 04/10 (Salva)
    - El modelo de datos de JavaScript
- 07/10 (Salva)
    - El modelo de datos de JavaScript: ejercicios

# 10-14 de octubre 

<!-- (Salva - max 3) -->

- 10/10 (Salva)
    - La cadena de prototipos
- 11/10 (Salva)
    - Closures
- 14/10 (Salva)
    - Programación asíncrona
    - Eventos: el patrón suscriptor / publicador

# 17-21 de octubre 

<!-- <1!-- (Belén - max 3) --1> -->

Tema 3: Programación de videojuegos en un canvas de HTML5

<!--  <1!-- x? --1> -->
- 17/10 (Belén)
    - Creación y acceso a un `canvas`
    - Canvas 2D/WebGL
    - Pintado y repintado, ciclo
    - Ciclo básico de juego en JavaScript
<!-- <1!-- x? --1> -->
- 18/10  (Belén)
    - Entrada básica 
    <!--. Clicks por lo menos  -->
    - Eventos navegador/DOM
    - Eventos con Phaser
<!--     ESTO NO DA TIEMPO    - Entrada avanzada (giro, accel, touch, pad…) -->
<!--     - Fullscreen: limitación (browsers fuerzan que fullscreen venga de un evento de usuario por seguridad) -->
<!-- <1!-- [2] --1> -->
- 21/10  (Belén)
    - Práctica 1: Batalla conversacional RPG

# 24-28 de octubre

<!-- prepara Carlos -->

Tema 4: Arquitectura de un motor de juegos en JavaScript: componentes y eventos

- 24/10 (Carlos)
    - Introducción a la arquitectura de videojuegos
    - Programación orientada a objetos (nociones/repaso)
- 25/10 (Carlos)
    - Componentes
- 28/10 (Ismael)
    - Ejercicios para evaluar: herencia vs. componentes
        - Sistema de combate RPG
   <!-- TODO [Carlos, 13-10-2016 15:35]: meter canvas, y comparación herencia
   vs. componentes -->

<!-- <1!-- Aquí revisitamos lo hecho hasta ahora y le damos un baño de componentes, sin meter low level javascript ni nada, sólo arquitectura --1> -->

# 31 de octubre - 4 de noviembre

<!-- prepara Ismael -->

Tema 5: Carga de recursos <!-- con Phaser -->

- 31/10 (Ismael)
    - Game states: carga y descarga de recursos. Pila de game states
    - URL/URIs
    - Localización de recursos
    - Carga en memoria
    - Uso y liberación de recursos
    <!-- - Spritesheets texturas (contar texturas? multitexturas phaser) -->
- 04/11 (Carlos)
    - Cargador de recursos para el juego
    - Cross-origin. Ejecutar Phaser en local server
    - Práctica 2: pintar plataformas

# 07-11 de noviembre 

<!-- Belen planifica día por día y nos repartimos los temas -->

Tema 6: Gestión de entidades (I)

<!-- <1!-- TODO [Carlos, 11-09-2016 14:38]: El 14 es fiesta --1> -->
<!-- (no sprites) esto tiene que venir antes de sprites -->

- 07/11 (Belén)
    - Imágenes
    - Creación y destrucción de entidades
- 08/11 (Belén)
    - Groups en Phaser
    - Sprite pools 
- 11/11 (Belén)
    - Práctica 2: Batallas RPG en el navegador

<!-- (spritepools no tiene que estar separada de grupos) -->

# 14-18 de noviembre 

Tema 6: Gestión de entidades (II)

- 14/11 (Belén)
    - Tiles 
    - Creación de tiles ([`tiled`](http://www.mapeditor.org/))
<!-- (prio 0) -->
 <!-- [0] -->
- 15/11 (Belén)
    - Texto 
    <!-- (prio 100) -->
    - Fuentes de mapa de bits
    - Fuentes Web y fuentes del sistema
- 18/11 (Belén)
    - Trabajo en Práctica 2

# 21-25 de noviembre

Tema 6: Gestión de entidades (III)

- 21/11 (Ismael)
    - Audio
    - Web Audio
    - Música y sonidos
- 22/11 (Carlos)
    - Audio en Phaser
    - Explicación juego arcade?
- 25/11 (Ismael)
    - Ejercicio con Web Audio
    - Trabajo en Práctica 2

# 28 de noviembre - 2 de diciembre

<!-- prepara ismael -->

<!-- TODO [Carlos, 13-10-2016 16:10]: Isma repasa esta plani -->

<!-- prepara ismael -->
Tema 7: Colisiones y triggers

- 28/11 (Ismael)
    - Colisiones básicas (rectángulos)
- 29/11 (Carlos)
    - *Overlapping*
    - *Triggers*
- 02/12 (Carlos)
    - Examen parcial

# 05-09 de diciembre

- 5/12 (Ismael)
    - Práctica 3: Juego de plataformas
- 9/12 (Ismael)
    - Trabajo en Práctica 3

# 12-16 de diciembre

Tema 8: Física para juegos en 2D

- 12/12 (Ismael)
    - Física simple
    - Bounding boxes
    - Física con Phaser
- 13/12 (Carlos)
    - Sistemas de colisiones *arcade*/*ninja*/*p2*
- 16/12 (Carlos)
    - Trabajo en Práctica 3


# 19-22 de diciembre

<!-- prepara Carlos -->

<!-- TODO [Carlos, 13-10-2016 16:12]: darle una vuelta a los items (Carlos) -->
Tema 9: Animaciones basadas en sprites

- 19/12 (Carlos)
    - Secuencias de sprites
    - Animación basada en secuencia
    - Ciclos de animación
- 20/12 (Carlos)
    - Spritesheets
    - Tweening
    - Animación por huesos
    <!-- TODO [Carlos, 13-10-2016 16:12]: ver Spine -->
- 23/12 (Ismael)
    - Trabajo en Práctica 4: Animaciones y física

# 9-13 de enero

<!-- la idea es que la práctica 5 tenga plug-ins y partículas, hay que cumplir
con el programa -->

Tutorías de proyecto

- 9/1 (Ismael)
    - Práctica 5: Plug-ins y *release*
- 10/1 (Carlos)
    - Tutorías
- 13/1 (Carlos)
    - Tutorías y trabajo en Práctica 5

# 16-20 de enero

Presentaciones

- 16/1 (Ismael)
    - Presentación de proyectos
- 17/1 (Carlos)
    - Presentación de proyectos
- 20/1 (Carlos)
    - Presentación de proyectos

