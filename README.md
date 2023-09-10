# Actividades de Reconociminento de Patrones en Imágenes
De un set de imágenes de texturas se realizan 3 actividades progresivas para identificar patrones para la clasificación de imágenes.

1. La Actividad 1 consiste en extraer los descriptores de una imagen compuesta por seis letras (sopa de letras). Las características a encontrar son:
    - 4 primeros momentos de Hu  
    - Perímetro  
    - Área
    - Redondez
    - Ángulo de orientación de la elipse
      
    El programa despliega:
    - Una matriz con los descriptores antes señalados
    - Una imagen que incluye cada letra con su centro de masa

2. La Actividad 2 consiste en encontrar el par de descriptores que maximicen las distancia entre clases (minimizando la distancia intra clase) de un set de imágenes de textura.
3. La Actividad 3 consiste en encontrar los descriptores que maximicen la distancia entre clases, realizar un feature selection considerando un criterio de información y modelar un clasificador, se selecciona entre varios modelos de acuerdo al F1-score promedio de 30 repeticiones por modelo.
