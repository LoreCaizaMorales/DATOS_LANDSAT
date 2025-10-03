# PREPARACIÓN DE LA SERIE TEMPORAL LANDSAT
La herramienta es un notebook en lenguaje Python que utiliza las librerías de GEE para automatizar la descarga de datos Landsat armonizados apartir de una archivo vectorial de puntos
1. Realiza una armonización de sensores Landsat
2. Aplica una mascara de nubes
3. Obtiene dos imagenes por mes
   * Una de los primeros 15 dias de cada mes
   * Otra de los 15 dias finales de fin de mes 
4. Calcula los indices NDVI, NBR, SAVI y TCG
5. Lee un archivo vectorial pre cargado en GEE
6. Corta la imagen segun un buffer seleccionado por el usuario
7. Genera la orden de descarga 
Los archivos son almacenados directamente en la carpeta de Drive designada por la cuenta de GEE.
Y están listos para aplicarse Edyn
# Aplicar EDYN
La herramienta Edyn esta disponible en el repositorio de su autor
Brooks, E.B., Yang, Z.Q., Thomas, V.A., and Wynne, R.H. Edyn: Dynamic Signaling of Changes to Forests Using Exponentially Weighted Moving Average Charts. Forests.
https://vtechworks.lib.vt.edu/items/accd5793-a8f6-4adf-afe5-d9e2712246c4

