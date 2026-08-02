# Observatorio Ambiental · Santiago de Cali (Prototipo)

Prototipo de rediseño del menú de categorías del Observatorio Ambiental de Cali,
con un sistema de iconos unificado (estilo, fondo y tipografía consistentes).

## Cómo ejecutarlo en VS Code

1. Descomprime esta carpeta y ábrela en VS Code (`Archivo > Abrir carpeta...`).
2. No necesita instalación ni dependencias: es HTML + CSS + JS puro en un solo archivo.
3. Para verlo en vivo con recarga automática, instala la extensión **Live Server**
   (Ritwick Dey) desde el panel de Extensiones de VS Code.
4. Clic derecho sobre `index.html` → **"Open with Live Server"**.
   (Alternativa sin extensión: abre `index.html` directamente en tu navegador
   con doble clic, o `Ctrl/Cmd + O` desde el navegador).

## Estructura

```
observatorio-ambiental-app/
├── index.html      # Todo el prototipo: HTML, CSS y JS inline
└── README.md
```

## Editar

Todo el diseño vive en `index.html`:
- Paleta y tipografías: bloque `:root { ... }` al inicio del `<style>`.
- Iconos: cada `<svg>` dentro de `.cat-card` (sección "Explorar por categoría").
- Datos simulados del panel "en vivo": bloque `<script>` al final del archivo.

## Nota

Este es un prototipo de diseño, no una integración con datos reales del
Observatorio Ambiental de Cali. Los valores de calidad del aire, ruido y
temperatura se generan aleatoriamente solo para ilustrar el concepto.
