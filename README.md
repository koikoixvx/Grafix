![Plataforma](https://img.shields.io/badge/Android-7.0%2B-3ddc84?logo=android&logoColor=white)
![Versión](https://img.shields.io/badge/versión-1.1--beta-a78bfa)
![Licencia](https://img.shields.io/badge/licencia-privada-lightgrey)
![Hecho con](https://img.shields.io/badge/hecho%20con-HTML%20%2B%20JS%20%2B%20Canvas-3b82f6)

# Inkvill

> Cuadernos, cómics y animación frame-by-frame en tu Android.
>
> ![Inkvill en acción](docs/screenshots/01-hero.png)
>## ¿Qué es Inkvill?

Inkvill es una app de dibujo para Android pensada para **cuadernos, cómics
y animación**. Cada libro tiene páginas con capas independientes, pinceles
personalizables, formas guía, texto y animación frame-by-frame con onion
skin.

Todo funciona **offline**. Tus dibujos se quedan en el teléfono.

- 🎨 **Dibujo con capas**: alpha lock, clipping mask, 16 modos de mezcla.
- 🖌️ **Pinceles**: grafito, tinta, acuarela, aerógrafo. Perfect-Freehand para trazos fluidos.
- 🎞️ **Animación**: fotogramas con duración variable, onion skin, ping-pong.
- ⏱️ **Timelapse automático** del proceso, exportable a vídeo.
- 📤 **Exporta** a PDF, PNG, ZIP, .grafix, GIF y vídeo.
- 🎭 **7 temas** de color, incluido modo E-Ink.
- 💾 **Backup** local (ZIP) y sincronización opcional con Google Drive.
- ## Capturas

| Canvas | Capas | Pinceles |
|---|---|---|
| ![Canvas](docs/screenshots/02-canvas.png) | ![Capas](docs/screenshots/03-layers.png) | ![Pinceles](docs/screenshots/04-brushes.png) |

| Animación | Exportar | Temas |
|---|---|---|
| ![Animación](docs/screenshots/05-animation.png) | ![Exportar](docs/screenshots/06-export.png) | ![Temas](docs/screenshots/07-themes.png) |

## En movimiento

[![Inkvill — demo](docs/screenshots/hero-video-thumb.png)](https://youtu.be/TU_VIDEO_ID)

Dibujo, capas y exportación en 30 segundos.

## Stack técnico

- **Frontend**: HTML + CSS + JavaScript vanilla (sin frameworks).
- **Empaquetado**: Capacitor 5 → Android WebView.
- **Persistencia**: IndexedDB para páginas/capas/timelapses, localStorage para ajustes.
- **Canvas**: motor de capas propio + Perfect-Freehand para el trazo.
- **Librerías**: page-flip, JSZip, jsPDF, html2canvas, gif.js, Kaitai Struct.
- **Fuente**: Inter (RIL OFL).

- ## Estado

**v1.1 · Beta**. Cerrando bugs de landscape, mejorando performance en gama baja.

Roadmap abierto en [Issues](../../issues).

Limitaciones conocidas:
- 1 animación por spread.
- Sin grupos de capas ni texto en curva.
- Sin export PSD.
- Importadores de pinceles (.abr, .png, .brushset) temporalmente desactivados.

- ## Agradecimientos

Construido sobre hombros de gigantes:

- **[Capacitor](https://capacitorjs.com/)** — puente entre web y Android.
- **[Perfect-Freehand](https://github.com/steveruizok/perfect-freehand)** — trazo fluido con presión.
- **[page-flip](https://github.com/Nodlik/StPageFlip)** — efecto curl del libro.
- **[JSZip](https://stuk.github.io/jszip/)** · **[jsPDF](https://github.com/parallax/jsPDF)** · **[html2canvas](https://html2canvas.hertzen.com/)** · **[gif.js](https://jnordberg.github.io/gif.js/)** — exportación.
- **[Kaitai Struct](https://kaitai.io/)** — parsing de archivos .abr.
- **[Inter](https://rsms.me/inter/)** (Rasmus Andersson, SIL OFL) — tipografía.

- 
> 
