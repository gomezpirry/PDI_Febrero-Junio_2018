# Homework Color Transformations

## Application: 0.0

* Main function of the application doesn't invocate the QApplication Object for display the GUI
* Review this line in __main.cpp__:

```
nuevaImagen->loadImage("C:/Users/Camilo/Desktop/I. procesamiento Digital de imagenes/Clase1/bear.jpg");
nuevaImagen->RgbToHsv();
nuevaImagen->saveImagen("C:/Users/Camilo/Desktop/I. procesamiento Digital de imagenes/ColorTransformation/datos.hsv");

```
 
If the bear.jpg file is not in application folder return invalid image

* Review this line:

```
nuevaImagen->saveImagen("datos.hsv");
```

__saveImagen__ function saves a .csv file and you pass as argument a string correspondent to .hsv file

* QApplication aren't invocated. GraphicsView objects generate run error

## Color Transformation Algorithms: 2.0

### RGB to HSV

* This block of code have an error:

```
else if ( var_G == var_Max ) H = ( 1 / 3 ) + del_R - del_B;
else if ( var_B == var_Max ) H = ( 2 / 3 ) + del_G - del_R;

```
 
(1/3) is an integer division and the result is 0.0 therefore there is a loss in decimal precision. The correct way is (1/3.0f) or (1.0f/3)

* Revies this block of code:

```
float aux1 = S*100;
float aux2 = V*100;
```

This values should not be multiplied by 100. Channels S and V have values between 0 and 1

### RGB to HSL

* Similar to RGB to HSV

# Grade: 1.0