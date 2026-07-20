# Graficas_lab1

## Hugo Méndez - 241265

Este proyecto implementa un framebuffer simple en Rust para dibujar líneas y rellenar polígonos mediante scanline fill.

## Características

- Creación de un framebuffer de tamaño configurable.
- Dibujo de líneas con algoritmo de Bresenham.
- Escritura de imágenes en formato BMP.
- Relleno de polígonos por scanline fill.

## Estructura del proyecto

- src/main.rs: programa principal donde se dibujan los polígonos.
- src/framebuffer.rs: implementación del framebuffer.
- src/line.rs: algoritmo de dibujo de líneas.
- src/bmp.rs: exportación de la imagen a BMP.
- src/scanlinefill.rs: algoritmo de relleno por scanline.

## Requisitos

- Rust instalado.
- Cargo.

## Cómo ejecutar

Desde la raíz del proyecto, ejecuta:

```bash
cargo run
```

Esto generará el archivo output.bmp con la imagen resultante.

## Notas

El programa actual dibuja varios polígonos y aplica relleno a algunas figuras, incluyendo el manejo de un hueco dentro de un polígono externo.