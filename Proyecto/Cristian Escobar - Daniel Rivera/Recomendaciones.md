## Proyecto PDI

* La aplicación solo lee placas con 6 caracteres, deberia leer mas caracteres
* Estan penalizando el error con un valor C muy grande, eso le reduce exactitud al entrenamiento `svm.SVC(gamma=0.001, C=100)` 
* Estan entrenando el clasificador svm con imagenes. Es recomendable, entrenarlo con descriptores porque si se entrena con imagenes, se puede introducir mucho ruido en el entrenamiento, ademas que se vuelva mas complejo computacionalmente
* Estan realizando una dilatación y una erosión por seperada. Pueden realizar una clausura y solo se hace una operación

### Nota: 4.3