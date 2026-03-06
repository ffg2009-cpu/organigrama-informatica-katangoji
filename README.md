# Organigrama Viewer

Visor interactivo del Plano Curricular — Engenharia Informática.

## Funcionalidades
- Pantalla completa (fondo 16:9)
- Zoom con botones, scroll del ratón, pellizco táctil
- Arrastrar para mover la imagen
- Imprimir en A4 apaisado
- Atajos de teclado: `+` zoom in · `-` zoom out · `0` reset · `Ctrl+P` imprimir

## Estructura del proyecto
```
organigrama-app/
├── index.html        ← aplicación principal
├── organigrama.png   ← imagen del organigrama
├── vercel.json       ← configuración Vercel
└── README.md
```

## Despliegue en Vercel vía GitHub

1. Crea un repositorio en GitHub y sube esta carpeta.
2. Ve a [vercel.com](https://vercel.com) → **Add New Project**.
3. Importa el repositorio de GitHub.
4. Vercel detecta automáticamente que es un sitio estático.
5. Haz clic en **Deploy** — ¡listo!

Cada `git push` a la rama principal desplegará automáticamente una nueva versión.
