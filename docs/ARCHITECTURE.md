# Arquitectura

## Flujo principal

Usuario
→ React
→ MapLibre
→ API server-side
→ Copernicus Data Space / Sentinel Hub
→ imagen + metadatos
→ visualización

## Análisis futuro

Imagen
→ procesamiento espectral
→ indicador (NDVI/NDWI/etc.)
→ datos cuantitativos
→ Gemini
→ interpretación explicada

## Regla de oro

La aplicación debe diferenciar siempre entre:

- **Observación:** lo que proviene del dato.
- **Cálculo:** lo que se obtiene mediante procesamiento.
- **Interpretación:** explicación generada por IA.

## Seguridad

Las credenciales privadas permanecen en servidor/Vercel. El cliente solicita únicamente los recursos que necesita.
