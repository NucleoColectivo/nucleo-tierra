# INSTRUCCIONES PARA GOOGLE AI STUDIO

Actúa como desarrollador senior frontend y creativo tecnológico para NÚCLEO / TIERRA.

Construye sobre el código existente. No reemplaces la arquitectura completa cuando una modificación localizada sea suficiente.

## Objetivo

Crear una aplicación experimental de observación territorial que combine cartografía interactiva, imágenes satelitales, series temporales, indicadores ambientales, interpretación asistida por IA y visualización generativa.

## Stack

- React
- TypeScript
- Vite
- MapLibre GL JS
- Copernicus Data Space / Sentinel Hub
- Vercel

## UX/UI

- Mobile first.
- Interfaz limpia, editorial y tecnológica.
- Evitar exceso de tarjetas y bordes redondeados.
- Contraste alto.
- Controles grandes y táctiles.
- Estados de carga y error claros.
- Navegación accesible por teclado.
- No depender únicamente del color.
- Estética experimental, territorial y contemporánea.

## Arquitectura

Separar:

1. mapa;
2. fuentes satelitales;
3. búsqueda de escenas;
4. procesamiento;
5. indicadores;
6. metadatos;
7. interpretación IA;
8. interfaz.

## Seguridad

Nunca colocar secretos en componentes React.

Usar variables de entorno y endpoints server-side cuando sea necesario.

Variables:

- COPERNICUS_CLIENT_ID
- COPERNICUS_CLIENT_SECRET
- GEMINI_API_KEY

Mantener el archivo de entorno local fuera de Git.

## Datos

Nunca presentar una inferencia de IA como si fuera un dato observado.

Mostrar fuente, fecha, producto, resolución y nubosidad cuando estén disponibles.

## IA

Gemini puede explicar datos y transformaciones, pero no debe inventar observaciones territoriales.

Separar visualmente:

**DATO → CÁLCULO → INTERPRETACIÓN**

## Código

- TypeScript estricto.
- Componentes pequeños.
- Dependencias mínimas.
- Nombres claros.
- No romper funcionalidades existentes.
- Revisar la arquitectura antes de cambios importantes.

## Antes de entregar

Verificar build, responsive, accesibilidad básica, manejo de errores, estados de carga y fuentes visibles.
