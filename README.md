# 🧩 GARNS – Sudoku de Howard Garns

> *"Un número en cada lugar, un lugar para cada número."*

Sudoku minimalista y progresivo con autoguardado, sonidos sintetizados a **432 Hz** y soporte **PWA** para jugar sin conexión. Hecho con ❤️ por Neto para Natalia.

![Demo](https://img.shields.io/badge/versión-1.0.0-gold?style=flat-square)
![PWA](https://img.shields.io/badge/PWA-lista-5aaa72?style=flat-square)
![Audio](https://img.shields.io/badge/audio-432Hz-b89840?style=flat-square)

---

## ✨ Características

- 🎯 **4 niveles de dificultad**: Fácil, Medio, Difícil, Experto.
- 💾 **Autoguardado** de partida (recarga la página y continúa donde lo dejaste).
- 🔊 **Sonidos sintetizados en 432 Hz** (correcto, error, combo, nivel completado, etc.).
- 🌌 **Atmósfera de fondo sutil** (se puede silenciar).
- 📦 **PWA completa** – instálala en tu móvil o escritorio y juega sin internet.
- ✍️ **Modo notas** para anotar posibles números.
- 💡 **Pistas** (hints) cuando te atasques.
- 🔥 **Sistema de combo y puntuación** que premia la velocidad y la precisión.
- 📊 **Estadísticas persistentes** (partidas jugadas, ganadas, mejores tiempos).

---

## 🎮 Cómo jugar

1. Elige una dificultad en el menú principal.
2. Toca una celda vacía y luego un número del teclado.
3. Usa el botón **📝** para activar el modo notas (anota candidatos).
4. Completa filas, columnas y cuadrantes para ganar puntos y aumentar tu combo.
5. Si te equivocas, el combo se reinicia. ¡Sé preciso!
6. Termina los 4 niveles para ver los créditos y escuchar la melodía de "500 miles".

---

## 🛠️ Tecnologías utilizadas

- **HTML5 / CSS3** – estructura y diseño minimalista.
- **JavaScript (ES6+)** – lógica del juego, autoguardado y PWA.
- **Web Audio API** – síntesis de sonidos en tiempo real (afinación 432 Hz).
- **Service Worker** – funcionalidad offline y caché.
- **LocalStorage** – persistencia de partida y estadísticas.

---

## 📦 Instalación local

Si quieres probar o modificar el juego en tu máquina:

```bash
git clone https://github.com/303Biznaga/Garns.git
cd garns
# Usa un servidor local (por ejemplo, Live Server de VS Code)
