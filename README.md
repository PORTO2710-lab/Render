# 🧊 RENDER - Interactive 3D Cube

Un visualizador interactivo construido con **Three.js** que demuestra el potencial de los gráficos 3D acelerados por hardware en la web.

## 🚀 Demo en vivo
Explora el cubo interactivo aquí: [https://porto2710-lab.github.io/Render/](https://porto2710-lab.github.io/Render/)

## ✨ Características
* **Interactividad Total:** Rota, desplaza y haz zoom sobre el objeto 3D.
* **Renderizado Realista:** Uso de luces direccionales y ambientales para simular profundidad.
* **Diseño Moderno:** Interfaz basada en tarjetas con estética Dark Mode.
* **Alto Rendimiento:** Optimizado mediante WebGL para una ejecución fluida en navegadores modernos.

## 🛠️ Stack Tecnológico
* **Three.js:** Motor de gráficos 3D.
* **JavaScript (ES6 Modules):** Lógica de la escena y controles.
* **CSS3:** Estilizado de la interfaz de usuario y layout responsivo.
* **HTML5 Canvas:** Lienzo de dibujo para el renderizador.

## 📦 Estructura de la Escena
* **Geometría:** `BoxGeometry(1.2, 1.2, 1.2)`
* **Materiales:** `MeshStandardMaterial` con colores vibrantes por cara.
* **Controles:** `OrbitControls` con amortiguación (damping) para movimientos suaves.

## ⚙️ Ejecución Local
1. Clona el repositorio:
   ```bash
   git clone [https://github.com/PORTO2710-lab/Render.git](https://github.com/PORTO2710-lab/Render.git)
