# Homework Color Transformations

## Application: 3.8

* The application does not allow to select the path to load and save image (You should use a QFileDialog) 
* As a recommendation, the (HSL - HSV) to RGB doesn't do any transformation 
* Try to name the functions with names that indicate something (i.e. __on_radioSubsampling_clicked__ instead of __on_function1_clicked__)

## Color Transformation Algorithms: 4.0

### RGB to HSV

* This block of code have an error:

```
else if(var_G == var_max){
    H = (1 / 3) + del_r - del_b;
}
else if(var_B == var_max){
    H = (2 / 3) + del_g - del_r;
}
```
 
(1/3) is an integer division and the result is 0.0 therefore there is a loss in decimal precision. The correct way is (1/3.0f)

### RGB to HSL

* Similar to RGB to HSV

# Grade: 3.9