# Lamp Architect — Configurador Paramétrico 3D de Lámparas

## Qué es
Configurador paramétrico 3D interactivo de lámparas artesanales de hilo de papel Kraft, con visualización en tiempo real y cálculo estructural automático.

## Stack
- React 18 (ESM/import maps, sin build)
- Three.js + React Three Fiber + Drei (3D)
- Tailwind CSS (CDN)
- Babel standalone (JSX en browser)
- Lucide React (iconos)

## Estructura
- **Archivo único**: `index.html` (~15 KB) — toda la app en un solo HTML
- Motor de cálculo estructural (longitud hilo, masa, tensión, factor seguridad)
- Componentes React 3D + UI glass-morphism
- Sin package.json, sin node_modules, sin build tools

## Deploy
- GitHub Pages via GitHub Actions
- URL: https://martinlleral.github.io/lamp-architect
- Zero build process — HTML estático directo

## Convenciones
- Todo en index.html (SPA monolítica sin build)
- CDN para todas las dependencias (esm.sh, unpkg)
- Compilación JSX via Babel en el navegador
