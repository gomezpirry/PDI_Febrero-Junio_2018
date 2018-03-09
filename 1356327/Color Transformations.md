# Homework Color Transformations

## Application: 5.0

* In general terms, the application satisfies all requeriments. As a recommendation, you can change the name of function associated to widget listeners (i.e. on_loadImageButton_clicked instead of on_pushButton_2_clicked) 

## Color Transformation Algorithms: 0.0

### RGB to HSV

* These instructions are incorrect for the problem environment:

```
QColor ClrCurrent(imagen.pixel(x,y));
r = qRgb(ClrCurrent.red(),0,0);
g = qRgb(0,ClrCurrent.red(),0);
b = qRgb(0,0,ClrCurrent.red());

var_r = (r/255);
var_g = (g/255);
var_b = (b/255);
```

 __qRgb__ is a typedef of unsigned int for the bit representation of \#AARRGGBB. You should get each color channel using ClrCurrent."channel_name"()
 
 * This instruction only change the value of one pixel:
 
 ```
 imagenHSV.setPixel(h,s,l);  /// correct way: imagenHSV.setPixel(x, y, qRgb(h, s, l))
 ```
 
 
### RGB to HSL

* Similar to RGB to HSV

# Grade: 2.5