# 🗺️ Roadmap — Inkvill Beta

## 🎯 Visión
Suite creativa con 3 pilares: **Esquemas**, **Libros**, **Notas**.

## ✅ Completado
- Arquitectura de 3 pilares.
- Pantallas de Esquemas y Notas con UI unificada.
- Herramienta de referencia v5.3.
- Galería de páginas v8.2.
- Navegación Android (`popstate`).

## 🔧 Próximas sesiones

| Idea | Prioridad |
|------|-----------|
| Implementar creación real de Esquemas (Personajes, Escenarios) con formularios y `localStorage`. | **Alta** |
| Ampliar editor de notas (autoguardado, negrita/cursiva, imágenes/URLs). | Media |
| Refinar Snap del carrusel (`proximity` → `mandatory`). | Baja |
| Botón `+` con más "pop" al pulsar. | Baja |
| Revisar vista Grid (animación escalonada al entrar). | Baja |
| Pulir modal de Exportación PDF (diseño y opciones). | Media |
| Revisar Page Manager (drag & drop con previews). | Media |

## 🎨 Decisiones de diseño
1. Tres pilares accesibles desde el footer del carrusel.
2. Unificación visual: header (flecha, título, lupa) + footer (`+` central).
3. Animaciones `translateY` al entrar/salir.
4. Navegación por `popstate` en Android.
5. Independencia de `localStorage` entre pilares.
