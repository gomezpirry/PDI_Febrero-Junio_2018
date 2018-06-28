## Proyecto PDI

* En la siguiente linea de codigo `imagenes.append(cv2.imread(imgstr))` estan creando un arreglo de matrices que corresponden a imagenes y para cada imagen sacan los contornos. Este proceso es innecesario y ademas consume demasiada memoria porque lo que necesitan es extraer los contorno. Pueden realizar en el ciclo la lectura de cada imagen y extraer los contornos y almacenarlo en el arreglo (El contorno es lo que importa) sin necesidad de tener todas las imagenes en memoria
* Para seleccionar solo contornos externos (No tomar en cuenta contornos internos) su usa el parametro `cv2. RETR_EXTERNAL` en lugar de `cv2.RETR_TREE`
* El k-means no funciona con repeticiones, el k-means calcula con distancias al centroide que corresponde a la clase. Los datos de entrenamiento alli se usan para posicionar mejor el centroide. El clasifica de acuerdo a la menor distancia que tiene el caracter que se quiere predecir con algun centroide y le dara la clase que tenga ese centroide

### Nota: 4.5