# Changelog — Inkvill

Todas las versiones notables de Inkvill.
Formato basado en [Keep a Changelog](https://keepachangelog.com/es/1.0.0/).

## [0.1.0-beta] — 2026-10-29

### Añadido
- **3 pilares**: Esquemas, Libros, Notas accesibles desde el footer del carrusel.
- `writer-notes.js`: sistema de notas independiente con UI unificada (flecha, título, lupa, `+` central), búsqueda con cierre al tocar fuera, animación de deslizamiento vertical.
- `scenes-writer.js`: módulo de Esquemas con tarjetas para Personajes, Escenarios y Plantillas de Storyboard (placeholder).
- Animación de entrada/salida (`translateY`) en pantallas secundarias.
- Integración con botón físico/gesto Android (`popstate`) para cerrar pantallas.
- Restauración correcta del carrusel al volver.

### Cambiado
- Unificación visual de las pantallas de Esquemas y Notas (header y footer compartidos).
- Eliminado toggle de "Modo Escritura" y placeholder de Esquemas de `app-features.js`.

### Corregido
- Rotación del carrusel al volver de pantallas secundarias.

---

## — Herramienta de Referencia

### Añadido
- Rotación, flip, multi/lineal, candado.
- Modo fantasma de ventana y modo inmersivo.
- Menú long-press, auto-deselección, snap a bordes.

### Eliminado
- Resize manual (reemplazado por snap).

---

## — Galería de Páginas

### Añadido
- Feedback táctil y tarjetas con sombra/presión.
- Selección por lado y lightbox.
- Export animática.

---

## [Sin versión] — Home Booster

### Añadido
- Actualización de "Editado hace X".
- Animación de entrada del home.
- Animación suave del sidebar de Ajustes.
- Textos de estado más grandes en violeta.
