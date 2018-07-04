## Aplicación PDI

### Operaciones Implementadas

* __Transformaciones de color:__ Implementada (4 pts)

* __Subsampling:__ No implementada (0 pts)
    * Esta calculando mal el subsampling, recorre de forma incorrecta la matriz

* __Reducción de bits:__ No implementada (0 pts)
    * Esta recorriendo de forma incorrecta la matriz

* __Filtros:__ Implementada (3 pts) 

* __Histograma:__ No implementada (0 pts)

* __Equalización del histograma:__ Implementada (1 pts)

* __Umbralización:__ Implementada (2 pts)

* __Detección de bordes:__ implementada parcialmente (2 pts)
    * Canny esta mal impelementado, no realiza la detección de bordes

* __Operadores morfológicos:__ Implementada parcialmente (5 pts)
    * La operación de erosion y dilatación no permite seleccionar el elemento estructurante
    * No estan implementadas las operaciones combinadas (apertura y clausura)
    
__Puntos: 17/24 (3,5)__


### Recomendaciones Generales

* En la interfaz, cuando se selecciona el subsampling realiza la reducción de bits y viceversa
* Poner identificadores significativos a los widgets de la interfaz (i.e.  on_pushButton no se sabe que boton es) 
* Los archivos quese subieron al campus eran solo para imágenes en escala de grises, para imágenes a color se tiene que trata cada canal de forma diferente 
* Utilizar el QFileDialog para cargar las imágenes


### Nota: 3,3