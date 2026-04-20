# ManTradu Models

Pesos y modelos ONNX para la app [ManTradu](https://github.com/Jhona11-v/ManTradu).

## Archivos

- `best.onnx` — YOLOv8 detector de texto/burbujas para manhwa/manga/manhua (~43 MB).
  - Clases: `clean_text` (diálogo), `messy_text` (SFX), `text_bubble` (globos).
  - Entrada: 1024x1024 RGB.
  - Entrenado a partir del proyecto Python `Manhua Translator v2.0`.

## Uso desde la app

La app descarga `best.onnx` bajo demanda desde:
```
https://github.com/Jhona11-v/mantradu-models/releases/download/v1/best.onnx
```
(o desde raw si se sirve por main: `https://raw.githubusercontent.com/Jhona11-v/mantradu-models/main/best.onnx`)
