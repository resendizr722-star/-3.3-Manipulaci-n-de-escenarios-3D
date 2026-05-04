# 🎮 3.3 Manipulación de Escenarios 3D

Aplicación web interactiva desarrollada con **Three.js**, que permite visualizar y manipular distintos escenarios 3D mediante controles avanzados.

---

## 🚀 Descripción

Este proyecto integra múltiples demos de Three.js en una sola interfaz tipo aplicación, permitiendo al usuario:

- Explorar distintos entornos 3D
- Interactuar con controles de cámara
- Manipular objetos en tiempo real
- Experimentar un entorno tipo videojuego con PointerLock

---

## 🧩 Características

✔ Visualización de múltiples escenas 3D  
✔ Navegación entre demos desde un menú lateral  
✔ Controles interactivos (Orbit, Map, Transform)  
✔ Modo videojuego con PointerLock  
✔ Botón de pantalla completa  
✔ Interfaz moderna tipo dashboard  
✔ Scroll controlado para mejor experiencia  

---

## 🎮 Demos incluidos

- 🟩 **Minecraft Terrain**  
  Generación de terreno tipo voxel usando ruido procedural  

- 🗺 **Map Controls**  
  Navegación tipo mapa (pan, zoom, desplazamiento)

- 🟡 **Orbit Controls**  
  Rotación libre alrededor de objetos  

- 🟥 **Transform Controls**  
  Manipulación de objetos (mover, rotar, escalar)

- 🎮 **PointerLock (FPS)**  
  Simulación de movimiento tipo videojuego en primera persona  

---

## 🛠 Tecnologías utilizadas

- [Three.js](https://threejs.org/)
- HTML5
- CSS3
- JavaScript (ES Modules)

---

## 📂 Estructura del proyecto
│
├── index.html
├── README.md
│
├── assets/
│ ├── css/
│ │ └── styles.css
│ └── js/
│
├── demos/
│ ├── webgl_geometry_minecraft.html
│ ├── misc_controls_map.html
│ ├── misc_controls_orbit.html
│ ├── misc_controls_transform.html
│ └── misc_controls_pointerlock.html
│
└── build/ (Three.js)