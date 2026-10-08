# SD-XL

**Autor:** Eduard Ávila

Programa para crear una imagen a partir de una descripción.

## Cómo ejecutarlo

Abre PowerShell en la carpeta del proyecto y ejecuta:

```powershell
uv sync
$env:HF_HUB_DISABLE_XET = "1"
uv run python src/sd_xl/__init__.py
```

Escribe la descripción cuando el programa la pida y pulsa Enter. El resultado se guarda como `imagen.png`. La primera vez necesita Internet para descargar el modelo y puede tardar.

Para abrir los archivos en Helix, usa `hx .` desde la carpeta del proyecto.

## Imagen del ejemplo

![Imagen del ejemplo](imagen.png)

La imagen incluida es la del ejemplo de clase. Al ejecutar el programa, se guarda una nueva imagen en su lugar.

Ejemplo de referencia: [repositorio original](https://github.com/fabianrodriguevara61-spec/SD-XL).

Modelo utilizado: [SDXL 1.0](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0).
