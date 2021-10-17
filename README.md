# Argentum Online

Este proyecto es un remake de Argentum Online, utilizando los mismos recursos pero con tecnología más actualizada.

El objetivo es mantener la misma escencia del juego brindando una solución diferente, repensando su arquitectura para evitar los problemas ya conocidos, mejorar la experiencia de usuario hasta el mas mínimo detalle y además sea escalable a futuro.

## Características principales
- Cliente para multiplataforma (Android, iOS, Windows, Linux, macOS)
- Servidor multiplataforma (Windows, Linux, macOS)
- Recursos basados en la liberación de FénixAO 1.0 (pueden ser reemplazados por otros)
- Mundo contínuo (unificando bordes de los actuales mapas)
- Diferente manejo de usuarios y áreas (uso de QuadTree)
- Mejoras en el manejo de gráficos (Uso de TextureAtlas, batch render, manejo de vértices)
- Características gráficas: (iluminación, partículas, shaders, etc)
- Abierto a varios modos de juego (modos que se desarrollan sobre la misma base)

## Tecnologías utilizadas:
- Cliente
  - [Kotlin](https://kotlinlang.org) (lenguaje principal) y Java
  - [libGDX](https://libgdx.com) (game development framework)
  - [libKTX](https://libktx.github.io) (extensiones de Kotlin para libGDX)
  - [ReduxKotlin](https://reduxkotlin.org) (manejo de estados basado en Redux)
  - [Koin](https://insert-koin.io) (para inyección de dependencias)

- Servidor
  - [Golang](https://golang.org) (lenguaje principal)
  