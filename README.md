# 🎰 Ruleta Bash Simulator

Un simulador de apuestas en la ruleta basado en dos estrategias populares: **Martingala** e **Inverse Labouchère**, desarrollado en **Bash**.  
Este proyecto tiene como propósito demostrar de manera práctica y educativa que, al final, **la casa siempre gana**.

---

## 🧠 Estrategias implementadas

- **Martingala**: Duplica tu apuesta cada vez que pierdes, esperando recuperar todo con una sola victoria.
- **Inverse Labouchère**: Estrategia que busca incrementar progresivamente las apuestas tras una victoria.

> ⚠️ Este proyecto **no promueve el juego con dinero real**. Está pensado como ejercicio técnico y educativo.

---

## 📦 Requisitos

- Bash (recomendado en un entorno Linux o macOS)
- Terminal compatible con secuencias ANSI (para colores)

---

## 🚀 Uso

```bash
./ruleta.sh -m <dinero_inicial> -t <estrategia>
```
Parámetros
-m: Dinero inicial para jugar (ejemplo: 100)

-t: Estrategia a utilizar: martingala o inverseLabouchere

Ejemplo
./ruleta.sh -m 100 -t martingala

📊 Objetivo
Este simulador está diseñado para poner a prueba estas estrategias en un entorno controlado. 
Verás cómo, incluso con métodos “matemáticamente sólidos”, el azar y los límites de capital te llevan inevitablemente a perder si juegas lo suficiente.

📁 Estructura del proyecto
ruleta.sh           # Script principal
README.md           # Este archivo

🧑‍💻 Autor
Rodrigo Inzaurralde


