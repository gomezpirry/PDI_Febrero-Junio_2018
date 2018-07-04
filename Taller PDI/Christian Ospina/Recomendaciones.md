## Aplicación PDI

### Operaciones Implementadas

* __Transformaciones de color:__ Implementada (4 pts)

* __Subsampling:__ No implementada (0 pts)
    * Esta calculando mal el subsampling, recorre de forma incorrecta la matriz

* __Reducción de bits:__ No implementada (0 pts)
    * Esta recorriendo de forma incorrecta la matriz

* __Filtros:__ Implementada (3 pts) 

* __Histograma:__ No implementada (1 pts)

* __Equalización del histograma:__ Implementada parcialmente (0,5 pts)
    * Calcula los nuevos valores de los piexeles con el histograma equalizado pero los asigna de forma incorrecta a la matriz de la imagen

* __Umbralización:__ No Implementada (0 pts)
    * No esta asignado de forma corretca los valores a los pixeles

* __Detección de bordes:__ implementada (3 pts)

* __Operadores morfológicos:__ Implementada parcialmente (7 pts)
    * La operación de erosion y dilatación no permite seleccionar el elemento estructurante
    * No estan implementadas las operaciones combinadas (apertura y clausura)
    
__Puntos: 18,5/24 (3,9)__


### Recomendaciones Generales

* Los archivos quese subieron al campus eran solo para imágenes en escala de grises, para imágenes a color se tiene que trata cada canal de forma diferente 


### Nota: 3,9