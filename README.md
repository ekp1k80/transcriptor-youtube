# Transcriptor de YouTube para Google Colab

Este repositorio contiene una página simple de GitHub Pages y el notebook de Colab. La página abre el notebook directamente y explica los tres pasos necesarios.

## Publicarlo en GitHub Pages

1. Creá un repositorio nuevo en GitHub y subí **estos dos archivos**: `index.html` y `youtube_whisper_turbo_colab.ipynb`.
2. En el repositorio, abrí `Settings` → `Pages`.
3. En **Build and deployment**, elegí `Deploy from a branch`.
4. Seleccioná la rama `main`, la carpeta `/(root)` y presioná `Save`.
5. Esperá uno o dos minutos. GitHub mostrará la URL pública, por ejemplo `https://tu-usuario.github.io/nombre-del-repo/`.

No hay que editar `index.html`: al publicarse en GitHub Pages, el botón detecta el usuario y repositorio y abre el notebook correspondiente en Google Colab.

## Qué hacen quienes lo usan

1. Abren la página pública y presionan **Abrir el transcriptor en Google Colab**.
2. En Colab presionan `Conectar` y `Entorno de ejecución` → `Ejecutar todas`.
3. Pegan una URL por línea, transcriben y descargan el ZIP.

Para Whisper Large-v3 Turbo se recomienda activar GPU T4 en Colab. Cada persona utiliza su propia sesión y su cuota de Colab.
