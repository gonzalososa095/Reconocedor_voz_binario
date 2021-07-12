# Reconocedor_voz_binario
CNN para reconocer hablantes.

* Descargar los archivos wav de https://drive.google.com/file/d/1SD0d3CE-9_v9qBlylUeIrYs10QK5H_4l/view?usp=sharing
* Descomprimir en la misma carpeta donde estan los demás archivos

## Pre_procesamiento.ipynb

Se hace un downsampling a 16 Khz y se dividen los archivos de audio para obtener muestras de 2 segundos. Los archivos procesados se guardan en las carpetas
'Archivos_procesados' y 'Archivos_procesados_test'

## main.ipynb

Se crea un modelo **conv1d**. Para la primer capa se realiza un espectograma usando la libreria **Kapre**

https://kapre.readthedocs.io/en/latest/
