# "**Situación problema: Contaminación ambiental y salud en México**"

## Artículo 2: Redes bayesianas gaussianas 

El cambio climático y la contaminación ambiental representan un desafío crítico para la salud humana. En particular, la exposición a contaminantes atmosféricos (como material particulado fino, ozono y dióxido de nitrógeno) ha sido asociada con alteraciones en biomarcadores biológicos relacionados con inflamación, función respiratoria y riesgo cardiovascular. Los contaminantes interactúan entre sí y con factores fisiológicos generando una red compleja de dependencias.

Las redes bayesianas gaussianas ofrecen una herramienta poderosa para modelar estas interacciones, permitiendo no solo describir dependencias, sino también realizar inferencias predictivas y simulaciones bajo distintos escenarios de exposición ambiental.

**Objetivo del proyecto:**
Implementar un modelo probabilístico que ayude a comprender cómo los factores ambientales influyen en la salud de la población mexicana, con el fin de ofrecer insumos para políticas públicas y estrategias de prevención.

**Estructura del repositorio:**
- Entrevistas : Carpeta con formato de entrevistas y dos entrevistas hechas a expertos médicos
- data : Carpeta con bases de datos utilizadas para muestras de salud y contaminantes ambientales, además se incluyen las bases de datos finales creadas para el análisis de DAGs
- figures : Carpeta con figuras de DAGs propuestas y gráficas de modelos lineal y no paramétrico
- Artículo_2_Final.qmd : Documento quarto de artículo científico
- Codigo_Artículo_2_Redes_bayesianas_gaussianas.qmd : Primer intento en limpiar y juntar bases de datos
- creacion_de_DAGs.qmd : Documento quarto de generación de DAGs, análisis de propuestas, network scores y utilización de modelo lineal y no paramétrico
- creacion_de_data.qmd : Documento quarto donde se realiza la limpieza de bases de datos, uniones entre ellas, verificaciones de datos, imputación KNN y creación de bases de datos finales
  
**Integrantes del equipo:**
- Barush Caliel C. Luna
- Diego B. Castillo
- Pedro Emilio S. Rodríguez
- Vidal Alejandro G. López
