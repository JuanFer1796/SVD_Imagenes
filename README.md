# SVD_Imagenes
Proyecto de compresión de imágenes utilizando SVD
Por supuesto, aquí está el texto sin el formato de código:

---

Este programa es una herramienta de compresión de imágenes que utiliza la Descomposición en Valores Singulares (SVD) para reducir el tamaño de las imágenes. Puede trabajar con imágenes en escala de grises y en RGB.

## Dependencias

Para ejecutar este programa necesitarás las siguientes librerías:

- os
- numpy
- matplotlib
- PIL
- skimage
- time

## Uso

Para usar este programa, debes tener una imagen en tu sistema de archivos local que desees comprimir.

Ejecuta el programa y sigue las instrucciones en pantalla. Se te pedirá que introduzcas la siguiente información:

- Ruta de la imagen: La ruta al archivo de imagen en tu sistema de archivos local.
- Modo de color: Elige entre "grayscale" (escala de grises) y "rgb".
- Número de componentes a mantener (`k`): Este número determina el número de componentes que se mantendrán en la compresión.
- Tamaño del bloque: Este número determina el tamaño de los bloques en los que se dividirá la imagen para la compresión.

Después de introducir esta información, el programa comprimirá la imagen y mostrará la tasa de compresión, así como una comparación visual de la imagen original y la imagen reconstruida.

## Advertencia

Este programa fue diseñado como una herramienta educativa y no se recomienda su uso para la compresión de imágenes en un contexto de producción. La calidad de la imagen reconstruida puede no ser adecuada para todos los usos.

---
