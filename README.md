#### SOBRE LA PLANTILLA
## Para  ejecutar en Overleaf  

1. Descargar el repositorio en .zip   
2. En Overleaf  'New Proyect' 
2.1. Selecciona Upload Proyect 
2.2. Selecciona el archivo descargado  en .zip
3. Dentro del proyecto en Overleaf  no comilara con el motor 'pdfLaTeX' por lo que se debe cambiar, en la seccion Menu -> Compiler -> seleccionar (XeLaTeX  o  LuaLaTeX)
4. Listo  recompila  el codigo y opten tu pdf para ser descargado.

## Otras recomendaciones

Los archivos principales son:
- TESIS_UNI_main.tex, archivo a ejecutar
- TesisUNI.cls, escrita por [Keyvin Saldaña](https://github.com/KeyvinSV), usando como base Book.cls (que viene en LaTeX por defecto)

Para obtener el PDF completo se debe ejecutar:  
```
pdflatex TESIS_UNI_main.tex
```
Con ello se obtiene **TESIS_UNI_main.pdf**



#### RECOMENDACIONES GENERALES PARA USAR LaTeX
- Usar [Python](https://www.python.org/) para obtener gráficos vectoriales, recomiendo emplear el repositorio [SciencePlots](https://github.com/garrettj403/SciencePlots).
- Gestionar la bibliografía con [Mendeley](https://www.mendeley.com/download-desktop-new/), que trabaja muy bien con LaTeX.
- Usar Illustrator y/o Autocad para generar imagenes vectoriales.
- Con el fin de facilitar la redacción, se pueden crear las Tablas en Excel y luego usar [Table Generator](https://www.tablesgenerator.com/) para convertirlas en formato LaTeX.
- Usar [Online LaTeX Equation Editor](https://latex.codecogs.com/eqneditor/editor.php) para escribir las formulas matemáticas de una manera rápida y eficiente .
