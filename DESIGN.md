---
version: "alpha"
name: "Registro de fuerza · Power Green"
description: "App móvil de registro de entrenamiento. Basada en la plantilla NVIDIA Power Green de designmd.app."
colors:
  primary: "#000000"
  secondary: "#ffffff"
  tertiary: "#76b900"
  neutral: "#111111"
  muted: "#a7a7a7"
  surface: "#bff230"
  accent: "#df6500"
typography:
  h1: { fontFamily: system-ui, fontSize: 30px, fontWeight: 700 }
  body-md: { fontFamily: system-ui, fontSize: 15px, fontWeight: 400 }
  label-caps: { fontFamily: ui-monospace, fontSize: 11px, fontWeight: 500 }
rounded: { sm: 2px }
---
## Overview
Se usa con una mano, entre series, con el móvil en el banco. Tiene que leerse de un vistazo
y no depender de la red. Todo el estilo está en el `<style>` de `index.html`.

## Colors
- Fondo negro `#000000`; tarjetas `#111111`; líneas `#2b2b2b` y `#5e5e5e`.
- Texto blanco; secundario `#a7a7a7`.
- Acento verde `#76b900`: bordes, pestaña activa, enlaces y foco. Como relleno solo en "Día completado".
- Naranja `#df6500`: sesión de tarde.
- La categoría del ejercicio se lee en el filete izquierdo: verde (tren superior), verde claro `#bff230` (inferior), blanco (core).

## Typography
- Fuente del sistema, peso 700 y mayúsculas en títulos.
- Monoespaciada del sistema para pesos, repeticiones, RM, fechas y rótulos.
- Sin fuentes externas.

## Layout
- Una columna, máximo 480px. Objetivos táctiles de 44px o más.
- Los campos de peso y repeticiones a 16px para que iOS no haga zoom.

## Elevation & Depth
Sin sombras, sin degradados, sin `backdrop-filter`.

## Shapes
Radio 2px en todo.

## Components
- Botón de acción: transparente con borde verde de 2px, texto en mayúsculas.
- Serie registrada: chip con borde, en monoespaciada.
- Listas (ejercicios, historial): filas separadas por una línea, dentro de un marco.

## Do's and Don'ts
- No más colores de acento.
- No emoji en la interfaz.
- No verde como fondo salvo en el estado completado.
