# CYBER SURGE: PROTOCOL ZERO ⚡ (2D & 2.5D DUAL ENGINE)

Un juego de plataformas retro-cyberpunk al estilo clásico de *Super Mario Bros*, diseñado con arquitectura híbrida para ser disfrutado tanto en **Modo 2D Retro Arcade** como en **Modo 2.5D Next-Gen WebGL (Three.js)** directamente en cualquier navegador web moderno.

![2D & 2.5D](https://img.shields.io/badge/Engine-2D%20%26%202.5D%20WebGL-00f0ff?style=flat-square)
![Three.js](https://img.shields.io/badge/Three.js-r128-ffe600?style=flat-square)
![HTML5 Canvas](https://img.shields.io/badge/HTML5-Canvas-00f0ff?style=flat-square)
![Web Audio API](https://img.shields.io/badge/Web%20Audio%20API-Procedural-ff0055?style=flat-square)
![Mobile Friendly](https://img.shields.io/badge/Mobile-Touch%20Controls-00ff66?style=flat-square)

---

## 🚀 Selector de Modo al Entrar

Al abrir el juego, se presenta un menú para elegir la experiencia de renderizado deseada:
1. **👾 Modo 2D Retro**: Motor Canvas clásico procedural con líneas de escaneo CRT (*scanlines*), viñeta y estética synthwave arcade de los 90.
2. **⚡ Modo 2.5D Next-Gen (Three.js)**: Gráficos 3D en tiempo real con WebGL, iluminación dinámica neón (cian, magenta, amarillo), proyección de sombras suaves (*soft shadows*), modelos poligonales 3D para el jugador y enemigos, y cámara cinemática que rastrea la acción con profundidad.

> Puedes alternar entre 2D y 2.5D en cualquier instante durante la partida pulsando el botón superior **`[ 🎮 MODO ]`** o la tecla **`C`**.

---

## 🕹️ Características Principales

- **Renderizado 100% Procedural en Canvas**: Todos los personajes, enemigos, fondos parallax, trampas y efectos visuales (scanlines CRT, viñeta, partículas, estelas *after-image*) están dibujados con primitivas de HTML5 Canvas. Sin imágenes externas ni dependencias pesadas.
- **Audio y Música Procedural (Web Audio API)**:
  - Sintetizador chiptune integrado que genera música retro en tiempo real.
  - El tempo (BPM) y la tonalidad/escala musical evolucionan dinámicamente con cada nivel.
  - Efectos de sonido (SFX) para saltos, pisotones, recolección de núcleos de datos, proyectiles láser, daño, fanfarria de nivel y fin de partida.
- **Motor de Físicas Sólido**:
  - Detección y resolución precisa de colisiones AABB.
  - Tolerancias arcade profesionales: *Coyote Time* y *Jump Buffering*.
  - Salto de altura variable (Mario-style): suelta la tecla para controlar la altura exacta del salto.
  - Mecánica clásica de pisotón sobre enemigos con rebote ascendente.
- **5 Niveles / Sectores con Dificultad Progresiva**:
  1. **Sector 1 - Neon Alley**: Introducción a los controles, saltos y drones de patrulla.
  2. **Sector 2 - Acid Foundry**: Lagos de ácido tóxico letales y plataformas móviles oscilantes.
  3. **Sector 3 - Laser Grid**: Barreras de láser intermitentes y torretas de plasma automatizadas.
  4. **Sector 4 - Skyline Nexus**: Alta verticalidad, abismos profundos, avispones aéreos y trampolines gravitacionales (*Jump Pads*).
  5. **Sector 5 - The Mainframe Apex**: Desafío final de máxima velocidad con el *Apex Sentinel* (persecución activa y disparos cargados).

---

## 🎮 Controles

| Acción | Teclas | Móvil / Pantalla Táctil |
| :--- | :--- | :--- |
| **Moverse a la izquierda** | `A` o Flecha `←` | Botón táctil `◀` |
| **Moverse a la derecha** | `D` o Flecha `→` | Botón táctil `▶` |
| **Saltar** | `Espacio`, `W` o Flecha `↑` | Botón táctil `▲ SALTO` |
| **Alternar Modo 2D / 2.5D 3D** | Tecla `C` | Botón superior `🎮 MODO` |
| **Invertir Mandos (Zurdo/Diestro)** | Tecla `I` | Botón superior `⇄ MANDOS` |
| **Silenciar / Activar Música y SFX** | `M` | Botón táctil `🔊 AUDIO` |
| **Reiniciar Sector / Partida** | `R` | Botón táctil `🔄 REINICIAR` |

---

## 🚀 Cómo Jugar

Simplemente abre el archivo `index.html` en cualquier navegador web moderno (Chrome, Firefox, Edge, Safari, Opera). No se requiere servidor local ni instalación.

### Jugar online en GitHub Pages
Para habilitar el juego online gratis con GitHub Pages:
1. Ve a tu repositorio en GitHub: `Settings` > `Pages`.
2. En **Branch**, selecciona `main` y la carpeta `/(root)`.
3. Haz clic en **Save**. En unos instantes estará disponible en:
   `https://<tu-usuario>.github.io/cybersurge/`
