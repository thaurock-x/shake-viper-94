# Snake Viper 94🐍⚡️

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/es/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)

**Snake Viper 94** es una reencarnación moderna y cibernética del clásico juego *Snake*, desarrollada completamente en **HTML5 Canvas, CSS3 y JavaScript vanilla**. Presenta una interfaz retro-futurista con efectos neon glow, curva de dificultad progresiva y soporte nativo para dispositivos móviles.

---

## 🚀 Características Principales:

- 🎨 **Estética Cyberpunk / Neon:** Interfaz oscura con degradados vibrantes y efectos de iluminación (`shadowBlur`) en la serpiente y la comida.

- ⚡ **Dificultad Dinámica:** A medida que la serpiente consume alimentos, la velocidad del juego se incrementa progresivamente.

- 🏆 **Sistema de Récord (Highscore):** Guardado automático de la puntuación máxima utilizando `localStorage`.

- 📱 **Diseño 100% Responsivo:** Adaptación fluida a diferentes tamaños de pantalla y dispositivos.

- 🎮 **Soporte Móvil Nativo:** D-Pad táctil en pantalla optimizado para baja latencia (`touchstart`).

- 🛑 **Control Anti-Suicidios:** Buffer de entrada (`nextDirection`) que evita giros accidentales de 180° en un solo frame.

- 📦 **Zero Dependencies:** Proyecto ultra ligero en un único archivo independiente sin librerías externas.

---

## 🎮 Controles
### 💻 Escritorio (Teclado):

| Acción | Teclas |
| :--- | :--- |
| **Moverse** | <kbd>↑</kbd> <kbd>↓</kbd> <kbd>←</kbd> <kbd>→</kbd> o <kbd>W</kbd> <kbd>A</kbd> <kbd>S</kbd> <kbd>D</kbd> |
| **Pausar** | <kbd>Espacio</kbd> |
| **Reiniciar** | <kbd>R</kbd> *(en pantalla de Game Over)* |

### 📱 Dispositivos Móviles:

- **D-Pad Táctil:** Usa las flechas en pantalla posicionadas en forma de cruz para cambiar la dirección.
- **Reiniciar:** Toca el botón **"Jugar de nuevo"** en la pantalla emergente.

---

## ⚙️ Mecánicas de Juego:

| Parámetro | Valor Inicial | Modificador / Condición |
| :--- | :--- | :--- |
| **Tamaño de Grilla** | $20 \times 20$ px | Cuadrícula de $24 \times 24$ celdas ($480 \times 480$ px) |
| **Velocidad Inicial** | $120\text{ ms}$ por frame | Reduce $3\text{ ms}$ por cada comida (Límite: $50\text{ ms}$) |
| **Puntuación** | $+10\text{ pts}$ | Por cada unidad de comida consumida |

---

## 🛠️ Instalación y Ejecución:

No requiere compilación ni instalación de servidor.

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/thaurock-x/snake-viper-94.git
   ```
---

### ​📄 Licencia:

<div align="center">
Desarrollado con 💚 por <strong>Thaurock</strong>
</div>

