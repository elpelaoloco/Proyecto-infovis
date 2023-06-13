 ## Ideas para visualizaciones
### Graficos
#### Grafico B
* Treemap dividido en categorias
    * Habitos (variables controlables, conducta)
    * Variables (variables incontrolables, ej enfermedades, genetica)
* Canales: Tamaño e intensidad de color  proporcionales con  la frecuencia de ataque cardiaco
#### Grafico A
* Circular Packing
    * Cada categoria encierre a las columnas que corresponde el tamaño codifica la proporcion
    * Cada categoria color distinto y todas las columnas  de un color
    * Hacer aun mas subdivisiones que en Treemap
        * Habitos
        * Enfermedades
        * Datos Personales
        
#### Grafico C
* Grafico de barras general para todas las columnas con la proporcion de enfermedades si son datos categoricos una barra para cada string. La idea esque  como en el link que viene sea vean todas las columnas diminutas y  ademas no tenga eje Y.
    * Mediante el click en categorias de grafico A se generara un zoom dentro del grafico hacia el donde estan los elementos de la categoria(tienen que estar los elementos de cada categoria juntos).
    Ademas el usuario tendra la opcion de interactuar directamente con el grafico sin haber hecho click en el grafico anterior.

    https://d3-graph-gallery.com/graph/area_brushZoom.html

### Informe
#### Primer Nivel
* Tematicas a considerar
    * Contexto, Naturaleza datos, Fuente y preprocesamiento, usuario herramienta, uso de herramienta

Las enfermedades cardíacas representan un desafío significativo para la salud pública en todo el mundo. Son responsables de un gran número de hospitalizaciones y muertes prematuras, afectando la calidad de vida de millones de personas. Estas enfermedades pueden ser causadas por una combinación de factores genéticos, estilo de vida y condiciones médicas subyacentes. Para abordar eficazmente este problema de salud global, es fundamental contar con herramientas que nos ayuden a comprender y visualizar de manera clara y efectiva la información relacionada con las enfermedades cardíacas.
En este contexto, presentamos una poderosa herramienta de visualización de información diseñada específicamente para ayudar a los profesionales de la salud y pacientes para que se pueda dar a conocer de manera sencilla los factores de riesgo para las enfermedades cardiacas.
De esta manera se logra concientizar a la poblacion sobre los factores de riesgo y lograr una prevencion temprana de enfermedades cardiacas.

El Dataset a trabajar corresponde a una encuesta telefonica  realizada  por el CDC (Centro de Control y Prevencion de Rnfermedades de Estados Unidos) el año 2020, esta encuesta trataba temas tales como habitos, historial medico, percepcion de salud actual y otros factores. 
Esto dio como resultado un set de datos estatico de  402.000 filas y 279 columnas que posteriormente fue reducida a las variables mas importantes quedando asi 18 columnas dentro de los cuales se encuentran variables categoricas, ordinales, cuantitaivass continuas y discretas
#### Segundo Nivel
* Tematicas a considerar
    * Analisis de datos, tareas

    