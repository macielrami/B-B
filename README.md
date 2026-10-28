 Bikes & Blades — Knights on Motorcycles
 
 ! ! ! ! EN DESAROLLO ! ! ! !

**Bikes & Blades** es un proyecto de videojuego de acción y combate sobre ruedas que fusiona la estética y mecánicas del combate medieval (espadas, lanzas y escudos) con la velocidad e inercia del motociclismo extremo. 

El desarrollo fue abordado bajo un enfoque **AI-native**, utilizando **Claude Code (CLI)** como agente de programación para la arquitectura del sistema, la gestión de estados de juego, la física de vehículos y la depuración iterativa.

---

## 🚀 Versiones e Implementaciones

El proyecto cuenta con dos implementaciones complementarias desarrolladas para testear mecánicas y escalabilidad:

### 1. 🕹️ Versión 2D (Prototipo Arcade / Web) DESAROLLO FASE MEDIANA
- **Motor / Framework:** JavaScript / Engine 2D
- **Propósito:** Prototipado rápido para validar el loop principal de juego, respuesta de controles y equilibrio de velocidad/combate.
- **Mecánicas clave:**
  - Control arcade lateral / vista top-down con física 2D simplificada.
  - Detección de colisiones y cálculo de daño según el impulso del vehículo.
  
### 2. 🎬 Versión 3D (Unreal Engine) EN DESAROLLO FASE INICIAL
- **Motor:** Unreal Engine
- **Arquitectura:** Lógica modular desarrollada junto a Claude Code CLI (Blueprints y C++).
- **Mecánicas clave:**
  - Sistema de física y tracción para motocicletas en entornos tridimensionales.
  - Combate cuerpo a cuerpo a alta velocidad con hitboxes precisos de ataque lateral y frontal.
  - Cámara en tercera persona dinámica con respuesta de impacto e inercia.
  - Manejo de estados de animación para el caballero y la postura de combate sobre el vehículo.



---

## 🤖 Flujo de Trabajo AI-Native (Claude Code CLI)

El desarrollo del proyecto se estructuró apoyándose en la terminal mediante **Claude Code**:

1. **Especificación e Iteración:** Traducción de conceptos de diseño de juego a lógica de código ejecutable.
2. **Máquinas de Estado:** Implementación asistida de estados para el personaje (*Idle, Riding, Attacking, Stunned, Crashed*).
3. **Debugging Iterativo:** Identificación y resolución de bugs en tiempo de ejecución directamente desde la terminal.
4. **Refactorización:** Mantenimiento de un código limpio, estructurado y documentado.

---

## 🎮 Mecánicas de Juego

- **Combate Inercial:** El daño infligido por las espadas y lanzas escala directamente con la velocidad de la moto al momento del impacto.
- **Manejo de Riscos y Curvas:** Control de derrape (*drift*) para mantener el ángulo de ataque frente a enemigos.
- **Dual-Mode System:** Posibilidad de experimentar la jugabilidad tanto en el visor 2D ultrarrápido como en el entorno inmersivo 3D.

---



- **Contacto / Desarrollador:** Ramiro Maciel — [macielrami10@gmail.com](mailto:macielrami10@gmail.com)

---

##
