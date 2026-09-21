# NÚCLEO / TIERRA

Laboratorio de observación territorial con imágenes satelitales, datos ambientales e inteligencia artificial.

## Concepto

NÚCLEO / TIERRA explora el territorio como un sistema vivo: permite observar imágenes satelitales, comparar momentos, visualizar índices ambientales y construir narrativas a partir de cambios detectados.

El proyecto combina **arte + territorio + datos + IA**.

## MVP

- Mapa interactivo mobile-first.
- Imágenes Sentinel-2 mediante Copernicus Data Space / Sentinel Hub.
- Selector de fecha.
- Visualización RGB.
- Capas ambientales preparadas para NDVI y NDWI.
- Comparación temporal.
- Panel de metadatos y fuente.
- Arquitectura preparada para análisis con IA.

## Stack

- React + TypeScript
- Vite
- MapLibre GL JS
- Copernicus Data Space / Sentinel Hub
- Vercel
- Gemini API (fase de análisis)

## Principios

1. Mobile first.
2. Accesibilidad desde el diseño.
3. Separar datos observados de interpretación generada por IA.
4. No exponer credenciales en el frontend.
5. Identificar siempre la fuente y fecha de los datos.
6. Código modular y fácil de evolucionar.
7. Priorizar herramientas abiertas y estándares interoperables.

## Desarrollo con Google AI Studio

Consultar [AI_INSTRUCTIONS.md](./AI_INSTRUCTIONS.md) antes de modificar el proyecto.

## Roadmap

Consultar [ROADMAP.md](./ROADMAP.md).

## Estado

**V0.0 — arquitectura inicial**

El siguiente objetivo es implementar el visor Sentinel-2 sobre MapLibre.
