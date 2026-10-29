# 🖋️ Inkvill — Beta

> **Suite Creativa** para dibujo, esquemas y notas. Tres pilares, un solo lienzo.

Inkvill evoluciona de una app de dibujo a una **suite creativa integral** con tres pilares accesibles desde la pantalla principal:

| Pilar | Icono | Módulo | Descripción |
|-------|-------|--------|-------------|
| **Esquemas** | `[Hoja]` | `scenes-writer.js` | Pre-producción: fichas de personajes, escenarios y plantillas de storyboard. |
| **Libros** | `[+]` | `app.js` | Estudio de dibujo, referencias, animación y storyboards. |
| **Notas** | `[Lápiz]` | `writer-notes.js` | Moodboards, ideas, texto y URLs. |

---

## ✨ Características principales

- 🎨 **Estudio de dibujo** con canvas, capas y páginas.
- 🖼️ **Herramienta de referencia .**: rotación, flip, multi/lineal, candado, snap a bordes, modo fantasma, modo inmersivo, menú long-press.
- 🗂️ **Galería de páginas .**: feedback táctil, tarjetas con sombra, selección por lado, lightbox, export animática.
- 📝 **Notas independientes**: interfaz unificada con búsqueda, autoguardado y `+` central.
- 🗒️ **Esquemas**: tarjetas para Personajes, Escenarios y Plantillas de Storyboard.

---

## 📸 Capturas

| Home | Estudio | Referencia |
|------|---------|------------|
| ![Home](docs/screenshots/01-home-carousel.png) | ![Estudio](docs/screenshots/02-book-studio.png) | ![Referencia](docs/screenshots/03-reference-tool.png) |

| Galería | Esquemas | Notas |
|---------|----------|-------|
| ![Galería](docs/screenshots/04-page-gallery.png) | ![Esquemas](docs/screenshots/05-scenes-schemas.png) | ![Notas](docs/screenshots/06-notes.png) |

---

## 🚧 Estado del proyecto

**Versión:** `0.1.0-beta`
**Estado:** Beta privada — arquitectura de 3 pilares completa.

### ✅ Completado
- Herramienta de referencia 
- Galería de páginas 
- Pantallas de Esquemas y Notas con UI unificada
- Animaciones de entrada/salida (`translateY`)
- Integración `popstate` Android
- Home Booster y sidebar de Ajustes animado

### 🔧 En progreso / Próximo
- Creación real de Esquemas (Personajes, Escenarios) con formularios y `localStorage`.
- Editor de notas ampliado (negrita/cursiva, imágenes, URLs).
- Refinar Snap del carrusel (`proximity` → `mandatory`).
- Pulir modal de Exportación PDF.
- Revisar Page Manager (drag & drop con previews).

Ver [`docs/ROADMAP.md`](docs/ROADMAP.md) para el detalle.

---

## 🛠️ Stack

- **HTML5 / CSS3 / JavaScript (vanilla)**
- **Canvas API**
- **localStorage** para persistencia
- Sin dependencias externas en runtime

---

## 📁 Estructura
