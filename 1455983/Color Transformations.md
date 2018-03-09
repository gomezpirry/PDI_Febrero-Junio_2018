# Homework Color Transformations

## Application: 5.0

* The application satifies all requirements

## Color Transformation Algorithms: 3.0

### RGB to HSV

* Please, you don't use variable identifier as "colorsito" 

* This block of code have an error:

```
else if(var_G == var_Max){
    H = (1 / 3) + del_R - del_B;
}
else if(var_B == var_Max){
    H = (2 / 3) + del_G - del_R;
}
```
 
(1/3) is an integer division and the result is 0.0 therefore there is a loss in decimal precision. The correct way is (1/3.0f)

### RGB to HSL

* Similar to RGB to HSV

# Grade: 4.0