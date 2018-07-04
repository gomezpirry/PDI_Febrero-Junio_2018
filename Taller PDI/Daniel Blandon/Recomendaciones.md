## Aplicación PDI

### Operaciones Implementadas

* __Transformaciones de color:__ Implementada (4 pts)

* __Subsampling:__ Implementada (1 pts)
    * Esta calculando mal el subsampling, recorre de forma incorrecta la matriz

* __Reducción de bits:__ Implementada (1 pts)
    * Esta recorriendo de forma incorrecta la matriz

* __Filtros:__ Implementada (3 pts) 

* __Histograma:__ No implementada (0 pts)

* __Equalización del histograma:__ No implementada (0 pts)
    * Calcula los nuevos valores de los piexeles con el histograma equalizado pero los asigna de forma incorrecta a la matriz de la imagen

* __Umbralización:__ No Implementada (0 pts)
    * La umbralización no es una operación de ecualización. esta operación debe retornar una imagen binaria

* __Detección de bordes:__ Implementada (2 pts)
    * No esta implementado canny

* __Operadores morfológicos:__ Implementada parcialmente (7 pts)
    * La operación de erosion y dilatación no permite seleccionar el elemento estructurante
    * No estan implementadas las operaciones combinadas (apertura y clausura)
    
__Puntos: 18/24 (3,8)__


### Recomendaciones Generales

* En la parte superior de la interfaz se encuentran las operaciones de transformacion de color pero no hacen nada. No es necesario agregarlas ahi si ya se encuentran en el combo box de lasoperaciones
* Los archivos que se subieron al campus eran solo para imágenes en escala de grises, para imágenes a color se tiene que trata cada canal de forma diferente 
* cada una de las operaciones se realizan sobre la imagen original, alli esta realizando las operaciones sobre la imagen ya operada


### Nota: 3,7