# 📜 Visual Adventure (Aventura Visual)

> **Motor propio para novelas interactivas y aventuras conversacionales en Android.**  
> *Lanzado originalmente en marzo de 2015.*

[![Year](https://img.shields.io/badge/Release-Marzo%202015-amber?style=flat-square&logo=calendar)](https://github.com/JoseMHR/TaosLegacyGames/tree/main/visual-adventure)
[![Platform](https://img.shields.io/badge/Platform-Android%204.0%2B-green?style=flat-square&logo=android)](https://github.com/JoseMHR/TaosLegacyGames/tree/main/visual-adventure)
[![Tech](https://img.shields.io/badge/Stack-Java%20%7C%20Eclipse%20ADT-blue?style=flat-square)](https://github.com/JoseMHR/TaosLegacyGames/tree/main/visual-adventure)

---

## 📖 Contexto e Historia

**Visual Adventure** fue el proyecto más ambicioso de mi etapa móvil de 2015: en lugar de un juego individual con contenido estático, fue el **diseño y construcción de un motor propio (*Engine*)** para crear novelas visuales, aventuras de misterio y juegos de rol narrativos basados en elecciones.

Cuenta con más de 40 commits históricos y un sistema modular completo que sentó las bases conceptuales que, 9 años más tarde, evolucionarían hacia mi motor insignia: **TaosGameMaker**.

Llegó a estar publicado en Google Play Store bajo el paquete `taos.timedestiny`.

---

## 🎮 Sistemas del Motor

* **Sistema de Actores y NPCs**: Gestión de personajes con atributos (físico, sociable, conocimientos) y retratos de diálogo dinámicos.
* **Sistema de Inventario (Bag)**: Mochila interactiva para recoger, inspeccionar y usar objetos en escenarios.
* **Navegación por Mapa**: Selector de ubicaciones conectadas entre sí para viajar por el mundo del juego.
* **Eventos y Diálogos Ramificados**: `EventoBase` extensible para desencadenar conversaciones, elecciones morales y bifurcaciones en la trama.
* **Soporte Multilenguaje**: Arquitectura preparada para textos en Español e Inglés con assets dedicados.
* **Guardado de Partida**: Sistema de persistencia para guardar y cargar estados de progreso.

---

## 📸 Galería de Capturas (2015)

<p align="center">
  <img src="./Screenshot/Spanish%20Version/MainMenu.png" width="30%" alt="Menú Principal" />
  <img src="./Screenshot/Spanish%20Version/Location.png" width="30%" alt="Escenario y Diálogo" />
  <img src="./Screenshot/Spanish%20Version/Map.png" width="30%" alt="Mapa de Navegación" />
</p>

<p align="center">
  <img src="./Screenshot/Spanish%20Version/Bag.png" width="30%" alt="Sistema de Inventario" />
  <img src="./Screenshot/Spanish%20Version/Actor.png" width="30%" alt="Ficha de Personaje" />
  <img src="./Screenshot/Spanish%20Version/Options.png" width="30%" alt="Opciones" />
</p>

---

## 🛠️ Retrospectiva Técnica

* **Arquitectura**: Patrón orientado a objetos con clases centrales como `EventoBase.java`, `Personaje.java`, `Objeto.java` y gestores de estado.
* **Germen de TaosGameMaker**: La idea de desacoplar los datos (inventario, eventos, actores) de la vista nació aquí y representa la semilla de lo que hoy en día es mi motor de JRPGs en Godot 4.3.

---

## 📦 Recursos y Código Fuente

* **Código Fuente Completo**: [`./VisualAdventure Source Code/`](./VisualAdventure%20Source%20Code/)
* **Galería Completa de Capturas**: [`./Screenshot/`](./Screenshot/)

---

[← Volver al Archivo Principal (TaosLegacyGames)](../README.md)
