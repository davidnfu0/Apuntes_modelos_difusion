# Apuntes sobre modelos de difusión

Los apuntes se pueden leer en la siguiente página web: https://davidnfu0.github.io/Apuntes_modelos_difusion/

Este repositorio contiene apuntes y recursos relacionados con modelos de difusión, una clase de modelos generativos que han ganado popularidad en los últimos años por su capacidad para generar datos de alta calidad, como imágenes, audio y texto.

El objetivo de estos apuntes es proporcionar una buena introducción a estos modelos desde el punto de vista del cálculo estocástico, cubriendo tanto los fundamentos teóricos como las implementaciones prácticas.

## Activar el entorno para ejecutar el código

Para ejecutar el código de los apuntes, es recomendable crear y activar un entorno virtual con las dependencias necesarias. Puedes hacerlo utilizando Conda con el siguiente comando:

```bash
conda env create -f environment.yml
conda activate quarto-diffusion
```

Registrar el entorno en Jupyter:

```bash
python -m ipykernel install --user --name quarto-diffusion --display-name "Python (quarto-diffusion)"
```

## Ejecutar página web de los apuntes

```bash
quarto publish gh-pages
```
