# Separador de Pistas

Separa una canción en pistas: voz, batería, bajo y el resto de instrumentos. Funciona en tu PC, sin subir el audio a ningún lado.

## Descarga

👉 [Descargar la última versión](https://github.com/amcaro82/SeparadorPistas-Descargas/releases/latest)

Baja el archivo `SeparadorPistas-Setup.exe` y ejecútalo.

## Requisitos

- Windows 10 u 11 de 64 bits
- Unos 3 GB libres en disco
- Internet la primera vez que uses cada algoritmo (descarga el modelo, unos 80 MB)

## Cómo se usa

1. Elige la canción (mp3, wav, flac, m4a, ogg o aac).
2. Elige dónde guardar las pistas.
3. Escoge el algoritmo, qué quieres separar, el formato y la calidad.
4. Dale a **Separar**.

Una canción de 4 minutos tarda entre 2 y 5 minutos, según tu PC.

## Algoritmos

| Algoritmo | Para qué |
|---|---|
| htdemucs | El recomendado. Rápido y buena calidad |
| htdemucs_ft | Mejor calidad, pero unas 4 veces más lento |
| htdemucs_6s | Separa también guitarra y piano |
| mdx_extra | Alternativa si los otros no te convencen |

## "Windows protegió su PC"

Puede salir este aviso porque el instalador no tiene firma digital. Haz clic en **Más información** → **Ejecutar de todas formas**.

## Créditos

Hecho por AMC.

Usa [Demucs](https://github.com/facebookresearch/demucs) (Meta, licencia MIT) para separar las pistas y [FFmpeg](https://ffmpeg.org) para convertir el audio.
