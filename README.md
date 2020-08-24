@Max Lugo D.

Tutorial Latex en español.

Para poder comenzar a usar latex es necesario instalar la paquetería correspondiente. 
Este breve tutorial describe los pasos para generar un primer documento de prueba en latex. 

Se debe de instarlar un interprete de latex y un editor de latex.
Interpretes: Miktex y Texlive. Se recomienda texlive. 
Editores: Texworks, lyx, texmaker, swp,... Se recomienda texmaker. 

Links de descarga:

Link para descargar texlive (se recomienda en la opción Full su instalación). 
https://tug.org/texlive/acquire-netinstall.html

Link para descargar texmaker
http://www.xm1math.net/texmaker/

Primero instalar el interprete (texlive) y después el editor (texmaker).

El texmaker utiliza un archivo .tex para crear un documento pdf mediante el interprete (miktex o texlive*). Aquí se anexan los archivos requeridos para comenzar. 

El archivo contiene:

1. doc.tex
2. apalike-es.bst
3. mybib.bib
4. Carpeta de imagenes y tex llamada Graphs_tables_maps (ejemplo para saber como traer imagenes)
5. hunspell.zip

El archivo tex llama a la bibliografía con el archivo mybib.bib (se descarga en repec o google la información bibliográfica). 
El archivo apalike-es.bst permite que el apartado de bibliografía diga bibiografía en vez de bibliography
(idioma español y no ingles). La carpeta Graphs_tables_maps contiene gráficos y tablas (ejemplos).

Nota: las gráficas son guardadas en formato vectorizado (.eps en este caso). 
Para corregir ortografía es necesario obtener el diccionario del idioma requerido (en español sería es.dic). 
La carpeta hunspell contiene diccionarios para diversos idiomas y países. No corrigen gramática.
No es necesario que el diccionario esté en la misma carpeta del archivo.tex. Su uso es opcional.

El archivo .tex contiene un formato de un artículo académico con los comandos para:
1. Poner titulo, autor, fecha, resumen inicial del artículo
2. Poner índice
3. Definir secciones
4. Escribir ecuaciones numeradas y no numeradas
5. Hacer tablas
6. Importar imagenes de una carpeta, tablas o texto (eps y tex respectivamente)
7. Citar
8. Poner la bibliografía
9. Poner notas al pie de página

Para abrir el archivo, una vez instalado las paqueterias, hay que realizar lo siguiente:
1. Abrir Texmaker
2. Abrir el doc.tex
3. En la parte superior está una opción con un signo de play. Ahi se encuentra quickbuilt, latex,... Se preciona bibtex (cargar la bibliografía) y play.
4. Se selecciona ahora PDFlatex y se pone play (esto debe generar un pdf con el documento doc.tex compilado)

Algunas veces hay que hacer el paso 3 y 4 varias veces para que cargue bien la bibliografía. Esto cubre una introducción para la creación de un primer documento básico. Explora el documento tex para familiarizarte con los comandos utilizados.




