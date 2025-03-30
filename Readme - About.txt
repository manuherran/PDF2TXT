PDF2TXT - Free OCR

By Manu Herrán
https://manuherran.com/

Este programa en Python procesa PDF aplicando OCR y generando TXT sobre una estructura recursiva de carpetas.

El programa ha sido creado usando software libre y es totalmente gratuito.

La herramienta genera ficheros TXT con el mismo nombre que el PDF original. Si el fichero TXT ya existía, lo sobreescribe.

Es importante tener en cuenta que si en la carpeta que contiene los PDF tenemos ficheros TXT con los mismos nombres que los PDF que van a ser procesados por este programa, los datos previos de los ficheros TXT (ficheros .txt) van a ser eliminados.

Este software se proporciona "tal cual", sin ninguna garantía. El autor no se hace responsable de ningún perjuicio o pérdida de datos causada por el uso de este programa.

Para poder ejecutar esta herramienta es necesario:

- Disponer de un equipo con Sistema Operativo Windows
- Instalar Visual Studio Code
https://code.visualstudio.com/download
- Instalar el intérprete de Python
https://www.python.org/downloads/
- Instalar tesseract en Windows
https://github.com/tesseract-ocr/tesseract  
https://tesseract-ocr.github.io/tessdoc/#binaries  
https://github.com/UB-Mannheim/tesseract/wiki  
https://github.com/tesseract-ocr/tesseract/releases/download/5.5.0/tesseract-ocr-w64-setup-5.5.0.20241111.exe  
- Instalar las librerías de Python pytesseract pdf2image Pillow
pytesseract: motor de OCR (Reconocimiento Óptico de Caracteres) de Tesseract.
pdf2image: convierte archivos PDF a imágenes.
Pillow: biblioteca para la manipulación de imágenes en Python.
Desde cmd:
pip install pytesseract pdf2image Pillow
- Abrir el programa PDF2TXT.ipynb con Visual Studio Code
- Seleccionar el intérprete de Python
- Confiar en el programa (Manage Restricted Mode, Trust)
- Modificar las últimas líneas del programa para seleccionar las carpetas a procesar
- Ejecutar el programa




