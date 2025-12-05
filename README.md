# Sensibilidad de la deshidratacion de raquiis de uva de mesa a partir de factores de precosecha.

Este repositorio presenta un fotografia de analisis visual de RGB a CIELAB para evaluar la sensibilidad de la deshidratacion del raquis de uva de mesa a partir de factores de precosecha. El analisis fue realizado usando Python y se enfoca en la relacion entre las caracterisiticas del raquis en la deshidratacion poscosecha. 

![Análisis de imágenes en el software python, separados por máscaras de porcentaje de verde, amarrillo y rojo](Figuras/Mascara_porcentaje.png)

## Hipotesis 

La sensibilidad del raquis a la deshidratación en poscosecha estaría determinada por características presentes al momento de la cosecha, por lo que es posible diagnosticar dicha sensibilidad mediante indicadores específicos del tejido.


## Objetivo 

Determinar la sensibilidad del raquis de uva de mesa a la deshidratación en poscosecha a través de los cambios que ocurren en el color y contenido de agua de este tejido durante la cosecha.


## Audiencia
Este repositorio está dirigido a estudiantes, investigadores y profesionales con interés en:

- La evaluación digital del color y la sensibilidad al pardeamiento del raquis en uva de mesa mediante análisis RGB–CIELAB.
- El desarrollo de modelos predictivos para cuantificar el riesgo de deshidratación y deterioro del raquis a partir de parámetros medidos en precosecha.
- El uso de Python para la automatización, visualización y análisis de datos provenientes de huertos comerciales y ensayos experimentales.



## 🗺️ Estructura del proyecto
El repositorio cuenta con dos carpetas principales: _code_ y _data_, que en conjunto tienen todos los archivos necesarios para reproducir el análisis exploratorio. Las carpetas _docs_, _figures_ y _quarto-website_ se utilizan para elaborar la página web con los resultados del análisis.

``` text
uva-de-mesa-2025/
├── README.md
├── Datos/
│   ├── Almacenamiento comercial.csv
│   ├── Base de datos.xlsx
│   ├── caracterizacion inicial.xlsx
│   ├── Contenido relativo de agua.csv
│   └── Pardeamiento uva de mesa.csv
│
├── docs/
│   └── Figuras/
│       └── Imagen1.png
│
├── Scripts/
│   ├── pardeamiento_uva.ipynb
│   └── pardeamiento_uva.qmd
```

### Datos
Los datos provienen de diferentes huertos de la zona central de chile de las varidades Allison y S.Celebration . 

## Agradecimientos
Esta investigación se realizo en el laboratio de poscosecha de la universidad de Chile y PRONABEC - Beca generación bicentenario, ademas a los productores que permitieron la recoleccion de fruta de su huertos. 


